<Type Name="ServiceGroupFactory" FullName="System.Fabric.ServiceGroupFactory">
  <TypeSignature Language="C#" Value="public sealed class ServiceGroupFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceGroupFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServiceGroupFactory" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceGroupFactory" />
  <TypeSignature Language="F#" Value="type ServiceGroupFactory = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Erstellt eine Dienstzuordnungsinstanz für die Gruppe, die mit dem tatsächlichen Dienstgruppen von den Factorys bereitgestellten Typs zur Laufzeit erstellt.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceGroupFactory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ServiceGroupFactory.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Erstellt ein leeres <see cref="T:System.Fabric.ServiceGroupFactory" />-Objekt.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddServiceType">
      <MemberSignature Language="C#" Value="public void AddServiceType (string serviceTypeName, Type serviceTypeImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddServiceType(string serviceTypeName, class System.Type serviceTypeImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ServiceGroupFactory.AddServiceType(System.String,System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddServiceType (serviceTypeName As String, serviceTypeImplementation As Type)" />
      <MemberSignature Language="F#" Value="member this.AddServiceType : string * Type -&gt; unit" Usage="serviceGroupFactory.AddServiceType (serviceTypeName, serviceTypeImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceTypeImplementation" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para>Der Diensttypname als Zeichenfolge. Es übereinstimmen, den Diensttyp, der im Manifest angegeben ist oder die <see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" /> von der <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> , bereitgestellt wird, während die <see cref="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription)" /> aufrufen.</para>
        </param>
        <param name="serviceTypeImplementation">
          <para>Der vollqualifizierte C#-Typ des Diensts, der der Service Fabric-Dienst implementiert.</para>
        </param>
        <summary>
          <para>Register ein bestimmter zustandsbehafteter oder statusfreier Dienst geben mit der Gruppe Dienstzuordnungsinstanz, sodass es als Mitglied der Gruppe "Service" erstellt werden kann.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddStatefulServiceFactory">
      <MemberSignature Language="C#" Value="public void AddStatefulServiceFactory (string serviceTypeName, System.Fabric.IStatefulServiceFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddStatefulServiceFactory(string serviceTypeName, class System.Fabric.IStatefulServiceFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ServiceGroupFactory.AddStatefulServiceFactory(System.String,System.Fabric.IStatefulServiceFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddStatefulServiceFactory (serviceTypeName As String, factory As IStatefulServiceFactory)" />
      <MemberSignature Language="F#" Value="member this.AddStatefulServiceFactory : string * System.Fabric.IStatefulServiceFactory -&gt; unit" Usage="serviceGroupFactory.AddStatefulServiceFactory (serviceTypeName, factory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatefulServiceFactory" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para>Gibt an, der Diensttypname als Zeichenfolge. Es übereinstimmen, den Diensttyp, der im Manifest angegeben ist oder die <see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" /> von der <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> , bereitgestellt wird, während die <see cref="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription)" /> aufrufen.</para>
        </param>
        <param name="factory">
          <para>Die Factory, einem zustandsbehafteten Dienst hinzufügen.</para>
        </param>
        <summary>
          <para>Die dienstfactory für die Gruppe hinzugefügt die Factory angegebenen zustandsbehaftete Dienst.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddStatelessServiceFactory">
      <MemberSignature Language="C#" Value="public void AddStatelessServiceFactory (string serviceTypeName, System.Fabric.IStatelessServiceFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddStatelessServiceFactory(string serviceTypeName, class System.Fabric.IStatelessServiceFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ServiceGroupFactory.AddStatelessServiceFactory(System.String,System.Fabric.IStatelessServiceFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddStatelessServiceFactory (serviceTypeName As String, factory As IStatelessServiceFactory)" />
      <MemberSignature Language="F#" Value="member this.AddStatelessServiceFactory : string * System.Fabric.IStatelessServiceFactory -&gt; unit" Usage="serviceGroupFactory.AddStatelessServiceFactory (serviceTypeName, factory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatelessServiceFactory" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para>Der Diensttypname als Zeichenfolge. Es übereinstimmen, den Diensttyp, der im Manifest angegeben ist oder die <see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" /> von der <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> , bereitgestellt wird, während die <see cref="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription)" /> aufrufen.</para>
        </param>
        <param name="factory">
          <para>Die hinzuzufügende zustandslosen Diensts-Factory.</para>
        </param>
        <summary>
          <para>Die dienstfactory für die Gruppe hinzugefügt die angegebenen zustandslosen dienstfactory.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveServiceFactory">
      <MemberSignature Language="C#" Value="public void RemoveServiceFactory (string serviceTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveServiceFactory(string serviceTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ServiceGroupFactory.RemoveServiceFactory(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveServiceFactory (serviceTypeName As String)" />
      <MemberSignature Language="F#" Value="member this.RemoveServiceFactory : string -&gt; unit" Usage="serviceGroupFactory.RemoveServiceFactory serviceTypeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para>Der Diensttypname als Zeichenfolge. Diese sollte den Diensttyp entsprechen, der angegeben wurde, wenn die Factory registriert wurde. </para>
        </param>
        <summary>
          <para>Entfernt die dienstfactory.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>