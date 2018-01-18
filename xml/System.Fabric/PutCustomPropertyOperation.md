<Type Name="PutCustomPropertyOperation" FullName="System.Fabric.PutCustomPropertyOperation">
  <TypeSignature Language="C#" Value="public sealed class PutCustomPropertyOperation : System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PutCustomPropertyOperation extends System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PutCustomPropertyOperation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PutCustomPropertyOperation&#xA;Inherits PropertyBatchOperation" />
  <TypeSignature Language="F#" Value="type PutCustomPropertyOperation = class&#xA;    inherit PropertyBatchOperation" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.PropertyBatchOperation</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="21f6f-101">Die angegebene Eigenschaft unter dem angegebenen Namen darstellt, und legt die benutzerdefinierte Typinformationen für benutzerdefinierte Interpretation des Eigenschaftswerts.</span><span class="sxs-lookup"><span data-stu-id="21f6f-101">Represents the specified property under the specified name and sets the custom type information for custom interpretation of the property value.</span></span></para>
    </summary>
    <remarks>
            <span data-ttu-id="21f6f-102">Der benutzerdefinierte Typ ist Informationen, die nicht vom Service Fabric verarbeitet, jedoch kann von Benutzer verwendet werden, um die Serialisierung/Deserialisierung von benutzerdefinierten Objekten.</span><span class="sxs-lookup"><span data-stu-id="21f6f-102">The custom type is information that is not processed by Service Fabric, but can be used by user to serialize/deserialize custom type objects.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutCustomPropertyOperation (string propertyName, byte[] value, string customTypeId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, unsigned int8[] value, string customTypeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutCustomPropertyOperation.#ctor(System.String,System.Byte[],System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Byte(), customTypeId As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutCustomPropertyOperation : string * byte[] * string -&gt; System.Fabric.PutCustomPropertyOperation" Usage="new System.Fabric.PutCustomPropertyOperation (propertyName, value, customTypeId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customTypeId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="21f6f-103">Der Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="21f6f-103">The name of the property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="21f6f-104">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="21f6f-104">The value for the property.</span></span></para>
        </param>
        <param name="customTypeId">
          <para><span data-ttu-id="21f6f-105">Der benutzerdefinierte benutzerdefinierten Typs.</span><span class="sxs-lookup"><span data-stu-id="21f6f-105">The user defined custom type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="21f6f-106">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.PutCustomPropertyOperation" /> Klasse mit dem angegebenen Eigenschaftennamen und Byte []-Wert, und legt der benutzerdefinierten Typ entsprechend.</span><span class="sxs-lookup"><span data-stu-id="21f6f-106">Initializes a new instance of the <see cref="T:System.Fabric.PutCustomPropertyOperation" /> class with the specified property name and byte[] value, and sets the custom type accordingly.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutCustomPropertyOperation (string propertyName, double value, string customTypeId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, float64 value, string customTypeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutCustomPropertyOperation.#ctor(System.String,System.Double,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Double, customTypeId As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutCustomPropertyOperation : string * double * string -&gt; System.Fabric.PutCustomPropertyOperation" Usage="new System.Fabric.PutCustomPropertyOperation (propertyName, value, customTypeId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Double" />
        <Parameter Name="customTypeId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="21f6f-107">Der Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="21f6f-107">The name of the property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="21f6f-108">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="21f6f-108">The value for the property.</span></span></para>
        </param>
        <param name="customTypeId">
          <para><span data-ttu-id="21f6f-109">Der benutzerdefinierte benutzerdefinierten Typs.</span><span class="sxs-lookup"><span data-stu-id="21f6f-109">The user defined custom type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="21f6f-110">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.PutCustomPropertyOperation" /> Klasse mit dem angegebenen Eigenschaftsnamen, und doppelte Wert und legt der benutzerdefinierten Typ entsprechend.</span><span class="sxs-lookup"><span data-stu-id="21f6f-110">Initializes a new instance of the <see cref="T:System.Fabric.PutCustomPropertyOperation" /> class with the specified property name and double value, and sets the custom type accordingly.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutCustomPropertyOperation (string propertyName, Guid value, string customTypeId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, valuetype System.Guid value, string customTypeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutCustomPropertyOperation.#ctor(System.String,System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Guid, customTypeId As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutCustomPropertyOperation : string * Guid * string -&gt; System.Fabric.PutCustomPropertyOperation" Usage="new System.Fabric.PutCustomPropertyOperation (propertyName, value, customTypeId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Guid" />
        <Parameter Name="customTypeId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="21f6f-111">Der Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="21f6f-111">The name of the property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="21f6f-112">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="21f6f-112">The value for the property.</span></span></para>
        </param>
        <param name="customTypeId">
          <para><span data-ttu-id="21f6f-113">Der benutzerdefinierte benutzerdefinierten Typs.</span><span class="sxs-lookup"><span data-stu-id="21f6f-113">The user defined custom type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="21f6f-114">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.PutCustomPropertyOperation" /> Klasse mit dem angegebenen Eigenschaftennamen und GUID-Wert, und legt der benutzerdefinierten Typ entsprechend.</span><span class="sxs-lookup"><span data-stu-id="21f6f-114">Initializes a new instance of the <see cref="T:System.Fabric.PutCustomPropertyOperation" /> class with the specified property name and GUID value, and sets the custom type accordingly.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutCustomPropertyOperation (string propertyName, long value, string customTypeId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, int64 value, string customTypeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutCustomPropertyOperation.#ctor(System.String,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Long, customTypeId As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutCustomPropertyOperation : string * int64 * string -&gt; System.Fabric.PutCustomPropertyOperation" Usage="new System.Fabric.PutCustomPropertyOperation (propertyName, value, customTypeId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Int64" />
        <Parameter Name="customTypeId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="21f6f-115">Der Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="21f6f-115">The name of the property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="21f6f-116">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="21f6f-116">The value for the property.</span></span></para>
        </param>
        <param name="customTypeId">
          <para><span data-ttu-id="21f6f-117">Der benutzerdefinierte benutzerdefinierten Typs.</span><span class="sxs-lookup"><span data-stu-id="21f6f-117">The user defined custom type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="21f6f-118">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.PutCustomPropertyOperation" /> Klasse mit dem angegebenen Eigenschaftennamen und Int64-Wert, und legt der benutzerdefinierten Typ entsprechend.</span><span class="sxs-lookup"><span data-stu-id="21f6f-118">Initializes a new instance of the <see cref="T:System.Fabric.PutCustomPropertyOperation" /> class with the specified property name and Int64 value, and sets the custom type accordingly.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutCustomPropertyOperation (string propertyName, string value, string customTypeId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, string value, string customTypeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutCustomPropertyOperation.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As String, customTypeId As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutCustomPropertyOperation : string * string * string -&gt; System.Fabric.PutCustomPropertyOperation" Usage="new System.Fabric.PutCustomPropertyOperation (propertyName, value, customTypeId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="customTypeId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="21f6f-119">Der Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="21f6f-119">The name of the property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="21f6f-120">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="21f6f-120">The value for the property.</span></span></para>
        </param>
        <param name="customTypeId">
          <para><span data-ttu-id="21f6f-121">Der benutzerdefinierte benutzerdefinierten Typs.</span><span class="sxs-lookup"><span data-stu-id="21f6f-121">The user defined custom type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="21f6f-122">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.PutCustomPropertyOperation" /> -Klasse mit dem angegebenen Eigenschaftennamen und String-Wert, und legt der benutzerdefinierten Typ entsprechend.</span><span class="sxs-lookup"><span data-stu-id="21f6f-122">Initializes a new instance of the <see cref="T:System.Fabric.PutCustomPropertyOperation" /> class with the specified property name and string value, and sets the custom type accordingly.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomTypeId">
      <MemberSignature Language="C#" Value="public string CustomTypeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomTypeId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PutCustomPropertyOperation.CustomTypeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomTypeId As String" />
      <MemberSignature Language="F#" Value="member this.CustomTypeId : string" Usage="System.Fabric.PutCustomPropertyOperation.CustomTypeId" />
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
          <para><span data-ttu-id="21f6f-123">Ruft die benutzerdefinierten Informationen ab.</span><span class="sxs-lookup"><span data-stu-id="21f6f-123">Gets the custom type information.</span></span> <span data-ttu-id="21f6f-124">Diese Informationen kann von Benutzern serialisieren/Deserialisieren benutzerdefinierten Objekten verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="21f6f-124">This information can be used by users to serialize/de-serialize custom type objects.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="21f6f-125">Die benutzerdefinierte Typinformationen.</span><span class="sxs-lookup"><span data-stu-id="21f6f-125">The custom type information.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyType">
      <MemberSignature Language="C#" Value="public System.Fabric.PropertyTypeId PropertyType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PropertyTypeId PropertyType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PutCustomPropertyOperation.PropertyType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyType As PropertyTypeId" />
      <MemberSignature Language="F#" Value="member this.PropertyType : System.Fabric.PropertyTypeId" Usage="System.Fabric.PutCustomPropertyOperation.PropertyType" />
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
          <para><span data-ttu-id="21f6f-126">Ruft den Eigenschaftentyp ab.</span><span class="sxs-lookup"><span data-stu-id="21f6f-126">Gets the property type.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="21f6f-127">Der Eigenschaftentyp.</span><span class="sxs-lookup"><span data-stu-id="21f6f-127">The property type.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyValue">
      <MemberSignature Language="C#" Value="public object PropertyValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object PropertyValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PutCustomPropertyOperation.PropertyValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyValue As Object" />
      <MemberSignature Language="F#" Value="member this.PropertyValue : obj" Usage="System.Fabric.PutCustomPropertyOperation.PropertyValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="21f6f-128">Ruft den Wert der Eigenschaft ab.</span><span class="sxs-lookup"><span data-stu-id="21f6f-128">Gets the property value.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="21f6f-129">Der Eigenschaftswert.</span><span class="sxs-lookup"><span data-stu-id="21f6f-129">The property value.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>