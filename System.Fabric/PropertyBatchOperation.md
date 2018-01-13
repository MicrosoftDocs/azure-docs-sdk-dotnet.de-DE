<Type Name="PropertyBatchOperation" FullName="System.Fabric.PropertyBatchOperation">
  <TypeSignature Language="C#" Value="public abstract class PropertyBatchOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit PropertyBatchOperation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class PropertyBatchOperation" />
  <TypeSignature Language="F#" Value="type PropertyBatchOperation = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.CheckExistsPropertyOperation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.CheckSequencePropertyOperation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.CheckValuePropertyOperation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.DeletePropertyOperation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.GetPropertyOperation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.PutCustomPropertyOperation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.PutPropertyOperation))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="2e9a3-101">Stellt die Basisklasse für die Eigenschaft-Vorgänge, die in einem Batch abgelegt werden können, und übermittelt werden, über die <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.SubmitPropertyBatchAsync(System.Uri,System.Collections.Generic.ICollection{System.Fabric.PropertyBatchOperation},System.TimeSpan,System.Threading.CancellationToken)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="2e9a3-101">Represents the base class for property operations that can be put into a batch and be submitted through the <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.SubmitPropertyBatchAsync(System.Uri,System.Collections.Generic.ICollection{System.Fabric.PropertyBatchOperation},System.TimeSpan,System.Threading.CancellationToken)" /> method.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="2e9a3-102">Beachten Sie, dass, wenn ein <see cref="T:System.Fabric.PropertyBatchOperation" /> Objekt ein Fehler auftritt, wird der gesamte Batch schlägt fehl, und kann nicht übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="2e9a3-102">Note that if one <see cref="T:System.Fabric.PropertyBatchOperation" /> object fails, the entire batch fails and cannot be committed.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected PropertyBatchOperation ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PropertyBatchOperation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="2e9a3-103">Initialisiert eine neue Instanz des <see cref="T:System.Fabric.PropertyBatchOperation" />-Objekts.</span><span class="sxs-lookup"><span data-stu-id="2e9a3-103">Initializes a new instance of the <see cref="T:System.Fabric.PropertyBatchOperation" /> object.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected PropertyBatchOperation (string propertyName, System.Fabric.PropertyBatchOperationKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string propertyName, valuetype System.Fabric.PropertyBatchOperationKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PropertyBatchOperation.#ctor(System.String,System.Fabric.PropertyBatchOperationKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (propertyName As String, kind As PropertyBatchOperationKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PropertyBatchOperation : string * System.Fabric.PropertyBatchOperationKind -&gt; System.Fabric.PropertyBatchOperation" Usage="new System.Fabric.PropertyBatchOperation (propertyName, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="kind" Type="System.Fabric.PropertyBatchOperationKind" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="2e9a3-104">Der Zeichenfolgenname der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2e9a3-104">String name of the Property.</span></span></para>
        </param>
        <param name="kind">
          <para>
            <span data-ttu-id="2e9a3-105"><see cref="T:System.Fabric.PropertyBatchOperationKind" />definiert die Art von der <see cref="T:System.Fabric.PropertyBatchOperation" />.</span><span class="sxs-lookup"><span data-stu-id="2e9a3-105"><see cref="T:System.Fabric.PropertyBatchOperationKind" /> defines the kind of the <see cref="T:System.Fabric.PropertyBatchOperation" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2e9a3-106">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.PropertyBatchOperation" /> Objekt mit dem angegebenen Eigenschaftennamen und die Art.</span><span class="sxs-lookup"><span data-stu-id="2e9a3-106">Initializes a new instance of the <see cref="T:System.Fabric.PropertyBatchOperation" /> object with the specified property name and kind.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public System.Fabric.PropertyBatchOperationKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PropertyBatchOperationKind Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyBatchOperation.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As PropertyBatchOperationKind" />
      <MemberSignature Language="F#" Value="member this.Kind : System.Fabric.PropertyBatchOperationKind" Usage="System.Fabric.PropertyBatchOperation.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PropertyBatchOperationKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2e9a3-107">Ruft die <see cref="T:System.Fabric.PropertyBatchOperationKind" /> , die gibt die Art von der <see cref="T:System.Fabric.PropertyBatchOperation" />.</span><span class="sxs-lookup"><span data-stu-id="2e9a3-107">Gets the <see cref="T:System.Fabric.PropertyBatchOperationKind" /> that indicates the kind of the <see cref="T:System.Fabric.PropertyBatchOperation" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2e9a3-108">Gibt <see cref="T:System.Fabric.PropertyBatchOperationKind" />zurück.</span><span class="sxs-lookup"><span data-stu-id="2e9a3-108">Returns <see cref="T:System.Fabric.PropertyBatchOperationKind" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="2e9a3-109">Alle Service Fabric-Enumerationen haben ein reserviertes Feld "Ungültig".</span><span class="sxs-lookup"><span data-stu-id="2e9a3-109">All Service Fabric enumerations have a reserved "Invalid" field.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyName">
      <MemberSignature Language="C#" Value="public string PropertyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PropertyName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyBatchOperation.PropertyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyName As String" />
      <MemberSignature Language="F#" Value="member this.PropertyName : string" Usage="System.Fabric.PropertyBatchOperation.PropertyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2e9a3-110">Gibt den Namen der Eigenschaft, die von diesem <see cref="T:System.Fabric.PropertyBatchOperation" /> zugreift.</span><span class="sxs-lookup"><span data-stu-id="2e9a3-110">Indicates the name of the property that this <see cref="T:System.Fabric.PropertyBatchOperation" /> accesses.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2e9a3-111">Gibt <see cref="T:System.String" />zurück.</span><span class="sxs-lookup"><span data-stu-id="2e9a3-111">Returns <see cref="T:System.String" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>