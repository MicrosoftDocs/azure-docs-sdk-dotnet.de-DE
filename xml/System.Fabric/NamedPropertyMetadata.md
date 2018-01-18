<Type Name="NamedPropertyMetadata" FullName="System.Fabric.NamedPropertyMetadata">
  <TypeSignature Language="C#" Value="public sealed class NamedPropertyMetadata" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NamedPropertyMetadata extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NamedPropertyMetadata" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NamedPropertyMetadata" />
  <TypeSignature Language="F#" Value="type NamedPropertyMetadata = class" />
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
      <para><span data-ttu-id="55d95-101">Die zugeordneten Metadaten einer <see cref="T:System.Fabric.NamedProperty" />, einschließlich der Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="55d95-101">The metadata associated with a <see cref="T:System.Fabric.NamedProperty" />, including the property’s name.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CustomTypeId">
      <MemberSignature Language="C#" Value="public string CustomTypeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomTypeId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.CustomTypeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomTypeId As String" />
      <MemberSignature Language="F#" Value="member this.CustomTypeId : string" Usage="System.Fabric.NamedPropertyMetadata.CustomTypeId" />
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
          <para><span data-ttu-id="55d95-102">Ruft die Id des benutzerdefinierten Typs.</span><span class="sxs-lookup"><span data-stu-id="55d95-102">Gets the custom type id.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="55d95-103">Die Id des benutzerdefinierten Typs.</span><span class="sxs-lookup"><span data-stu-id="55d95-103">The custom type id.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="55d95-104">Diese Eigenschaft verwenden, ist der Benutzer in der Lage, kennzeichnen den Typ des Werts der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="55d95-104">Using this property, the user is able to tag the type of the value of the property.</span></span> <span data-ttu-id="55d95-105">Im folgenden werden häufige Anwendungsfall für diese Eigenschaft ist.</span><span class="sxs-lookup"><span data-stu-id="55d95-105">Common use case for this property is the following.</span></span> <span data-ttu-id="55d95-106">Angenommen Sie, Sie Eigenschaft mit dem Namen der Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="55d95-106">Assume you have property called configuration.</span></span> <span data-ttu-id="55d95-107">Der Wert dieser Eigenschaft kann JSON oder XML sein, je nachdem, wer die Eigenschaft zuletzt aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="55d95-107">The value of this property can be JSON or XML, depending on who last updated the property.</span></span> <span data-ttu-id="55d95-108">In diesem Szenario können die Updater benutzerdefinierten Typ-Id-Eigenschaft Sie um den Typ der Eigenschaft an den Consumer der Eigenschaft zu kommunizieren.</span><span class="sxs-lookup"><span data-stu-id="55d95-108">In this scenario the updaters can use custom type id property to communicate the type of the property to the consumer of the property.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedUtc">
      <MemberSignature Language="C#" Value="public DateTime LastModifiedUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastModifiedUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.LastModifiedUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastModifiedUtc : DateTime" Usage="System.Fabric.NamedPropertyMetadata.LastModifiedUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="55d95-109">Ruft die Eigenschaft zuletzt geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="55d95-109">Gets when the Property was last modified.</span></span> <span data-ttu-id="55d95-110">Nur Schreibvorgänge führt dazu, dass dieses Feld aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="55d95-110">Only write operations will cause this field to be updated.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="55d95-111">Der Zeitpunkt der letzten, an die Eigenschaft geändert wurde, UTC.</span><span class="sxs-lookup"><span data-stu-id="55d95-111">The last time the property was modified, UTC.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parent">
      <MemberSignature Language="C#" Value="public Uri Parent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Parent" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.Parent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parent As Uri" />
      <MemberSignature Language="F#" Value="member this.Parent : Uri" Usage="System.Fabric.NamedPropertyMetadata.Parent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="55d95-112">Ruft den Namen des übergeordneten Elements Service Fabric-Namen für die Eigenschaft ab.</span><span class="sxs-lookup"><span data-stu-id="55d95-112">Gets the name of the parent Service Fabric Name for the Property.</span></span> <span data-ttu-id="55d95-113">Sie können als der namespacetabelle betrachtet werden unter dem die Eigenschaft vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="55d95-113">It could be thought of as the namespace/table under which the property exists.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="55d95-114">Der Name des übergeordneten Elements Service Fabric-Namen für die Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="55d95-114">The name of the parent Service Fabric Name for the Property.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyName">
      <MemberSignature Language="C#" Value="public string PropertyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PropertyName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.PropertyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyName As String" />
      <MemberSignature Language="F#" Value="member this.PropertyName : string" Usage="System.Fabric.NamedPropertyMetadata.PropertyName" />
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
          <para><span data-ttu-id="55d95-115">Ruft den Namen der Eigenschaft ab.</span><span class="sxs-lookup"><span data-stu-id="55d95-115">Gets the name of the Property.</span></span> <span data-ttu-id="55d95-116">Sie können der als Schlüssel für ein Schlüssel-Wert-Paar betrachtet werden.</span><span class="sxs-lookup"><span data-stu-id="55d95-116">It could be thought of as the key for a key value pair.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="55d95-117">Der Eigenschaftenname.</span><span class="sxs-lookup"><span data-stu-id="55d95-117">The property name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="System.Fabric.NamedPropertyMetadata.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="55d95-118">Ruft die Version der Eigenschaft ab.</span><span class="sxs-lookup"><span data-stu-id="55d95-118">Gets the version of the Property.</span></span> <span data-ttu-id="55d95-119">Jedes Mal, wenn eine Eigenschaft geändert wird, wird seine Sequenznummer erhöht.</span><span class="sxs-lookup"><span data-stu-id="55d95-119">Every time a Property is modified, its sequence number is increased.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="55d95-120">Die Version der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="55d95-120">The version of the property.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="55d95-121">Sequenznummern werden garantiert werden, um immer zu erhöhen.</span><span class="sxs-lookup"><span data-stu-id="55d95-121">Sequence numbers will be guaranteed to always increase.</span></span> <span data-ttu-id="55d95-122">Allerdings die Erhöhung der monoton möglicherweise nicht.</span><span class="sxs-lookup"><span data-stu-id="55d95-122">However, the increase may not be monotonic.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeId">
      <MemberSignature Language="C#" Value="public System.Fabric.PropertyTypeId TypeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PropertyTypeId TypeId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.TypeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TypeId As PropertyTypeId" />
      <MemberSignature Language="F#" Value="member this.TypeId : System.Fabric.PropertyTypeId" Usage="System.Fabric.NamedPropertyMetadata.TypeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PropertyTypeId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="55d95-123">Gibt an, ob der Wert der Eigenschaft eine Binärdatei <see cref="T:System.Int64" />, <see cref="T:System.Double" />, <see cref="T:System.String" /> oder <see cref="T:System.Guid" />.</span><span class="sxs-lookup"><span data-stu-id="55d95-123">Indicates whether the value of the Property is a Binary, <see cref="T:System.Int64" />, <see cref="T:System.Double" />, <see cref="T:System.String" /> or <see cref="T:System.Guid" />.</span></span> <span data-ttu-id="55d95-124">Eine häufige Verwendung dieses Feld ist zum Bestimmen des Typs mit dem <see cref="M:System.Fabric.NamedProperty.GetValue``1" />.</span><span class="sxs-lookup"><span data-stu-id="55d95-124">A common use of this field is to determine the type to use for the <see cref="M:System.Fabric.NamedProperty.GetValue``1" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="55d95-125">Die Eigenschaftentyp der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="55d95-125">The property type of the property.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="55d95-126">Alle Service Fabric-Enumerationen haben einen ungültige reservierten Wert.</span><span class="sxs-lookup"><span data-stu-id="55d95-126">All Service Fabric enumerations have a reserved Invalid value.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValueSize">
      <MemberSignature Language="C#" Value="public int ValueSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ValueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.ValueSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ValueSize As Integer" />
      <MemberSignature Language="F#" Value="member this.ValueSize : int" Usage="System.Fabric.NamedPropertyMetadata.ValueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="55d95-127">Gibt die Länge des Werts der serialisierten an.</span><span class="sxs-lookup"><span data-stu-id="55d95-127">Indicates the length of the serialized Property value.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="55d95-128">Die Länge des Werts der serialisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="55d95-128">The length of the serialized Property value.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>