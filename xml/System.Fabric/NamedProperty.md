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
      <para><span data-ttu-id="26fc0-101">Stellt eine Eigenschaft, die verwaltet wird die <see cref="T:System.Fabric.FabricClient.PropertyManagementClient" />.</span><span class="sxs-lookup"><span data-stu-id="26fc0-101">Represents a property that is managed by using the <see cref="T:System.Fabric.FabricClient.PropertyManagementClient" />.</span></span></para>
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
          <para><span data-ttu-id="26fc0-102">Der Typ des Eigenschaftswerts.</span><span class="sxs-lookup"><span data-stu-id="26fc0-102">The type of the property value.</span></span></para>
        </typeparam>
        <summary>
          <para><span data-ttu-id="26fc0-103">Ruft den Wert der Eigenschaft ab.</span><span class="sxs-lookup"><span data-stu-id="26fc0-103">Gets the value of the property.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="26fc0-104">Der Wert der Eigenschaft als Typ <typeparamref name="T" />.</span><span class="sxs-lookup"><span data-stu-id="26fc0-104">The value of the property as type <typeparamref name="T" />.</span></span></para>
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
          <para><span data-ttu-id="26fc0-105">Ruft die Metadaten, die enthält den Namen der Eigenschaft zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="26fc0-105">Gets the metadata that is associated with the property, which includes its name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="26fc0-106">Die Metadaten, die enthält den Namen der Eigenschaft zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="26fc0-106">The metadata that is associated with the property, which includes its name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>