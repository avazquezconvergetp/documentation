TEST1
==============

.. toctree::
   :titlesonly:

   test1/test_content1
   test2/test_content2

Short introduction
------------------

Write a brief intro here explaining what this document is about.

Prerequisites
-------------

- Item 1
- Item 2
- Item 3

Main Content
------------

Subsection 1
~~~~~~~~~~~~

Details about subsection 1.

Subsection 2
~~~~~~~~~~~~

Details about subsection 2.

Notes and Tips
--------------

.. note::
   This is a helpful note using a Sphinx directive.

.. warning::
   Be careful with this part of the process.

.. code-block:: xml

    <record id="view_id" model="ir.ui.view">
        <field name="name">view.name</field>
        <field name="model">object_name</field>
        <field name="priority" eval="16"/>
        <field name="arch" type="xml">
            <tree>
                <field name="my_field_1"/>
                <field name="my_field_2" string="My Label" widget="statusbar" statusbar_visible="draft,sent,progress,done" />
            </tree>
        </field>
    </record>

References
----------

- `Official docs <https://example.com>`_
- See also :ref:`another-section`