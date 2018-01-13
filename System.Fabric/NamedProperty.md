<Type Name="NamedProperty" FullName="System.Fabric.NamedProperty">
  <TypeSignature Language="C#" Value="public sealed class NamedProperty" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NamedProperty extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NamedProperty" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NamedProperty" />
  <TypeSignature Language="F#" Value="type NamedProperty = class" />
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
      <para>Stellt eine Eigenschaft, die verwaltet wird die <see cref="T:System.Fabric.FabricClient.PropertyManagementClient" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetValue&lt;T&gt;">
      <MemberSignature Language="C#" Value="public T GetValue&lt;T&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !!T GetValue&lt;T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NamedProperty.GetValue``1" />
      <MemberSignature Language="VB.NET" Value="Public Function GetValue(Of T) () As T" />
      <MemberSignature Language="F#" Value="member this.GetValue : unit -&gt; 'T" Usage="namedProperty.GetValue " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">
          <para>Der Typ des Eigenschaftswerts.</para>
        </typeparam>
        <summary>
          <para>Ruft den Wert der Eigenschaft ab.</para>
        </summary>
        <returns>
          <para>Der Wert der Eigenschaft als Typ <typeparamref name="T" />.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Fabric.NamedPropertyMetadata Metadata { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.NamedPropertyMetadata Metadata" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedProperty.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metadata As NamedPropertyMetadata" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Fabric.NamedPropertyMetadata" Usage="System.Fabric.NamedProperty.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NamedPropertyMetadata</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Metadaten, die enthält den Namen der Eigenschaft zugeordnet wird.</para>
        </summary>
        <value>
          <para>Die Metadaten, die enthält den Namen der Eigenschaft zugeordnet wird.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>