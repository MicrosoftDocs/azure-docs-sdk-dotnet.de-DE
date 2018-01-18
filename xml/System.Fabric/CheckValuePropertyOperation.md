<Type Name="CheckValuePropertyOperation" FullName="System.Fabric.CheckValuePropertyOperation">
  <TypeSignature Language="C#" Value="public sealed class CheckValuePropertyOperation : System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CheckValuePropertyOperation extends System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.CheckValuePropertyOperation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CheckValuePropertyOperation&#xA;Inherits PropertyBatchOperation" />
  <TypeSignature Language="F#" Value="type CheckValuePropertyOperation = class&#xA;    inherit PropertyBatchOperation" />
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
      <para><span data-ttu-id="f7b40-101">Stellt eine <see cref="T:System.Fabric.PropertyBatchOperation" /> , vergleicht den Wert der Eigenschaft mit dem erwarteten Wert.</span><span class="sxs-lookup"><span data-stu-id="f7b40-101">Represents a <see cref="T:System.Fabric.PropertyBatchOperation" /> that compares the value of the property with the expected value.</span></span>  </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="f7b40-102">Der Vergleich schlägt fehl, wenn der Wert der Eigenschaft und dem erwarteten Wert nicht gleich sind.</span><span class="sxs-lookup"><span data-stu-id="f7b40-102">The comparison fails if the value of the property and the expected value are not equal.</span></span> <span data-ttu-id="f7b40-103">Die <see cref="T:System.Fabric.CheckValuePropertyOperation" /> wird im Allgemeinen als Voraussetzung für die Write-Vorgänge im Batch verwendet.</span><span class="sxs-lookup"><span data-stu-id="f7b40-103">The <see cref="T:System.Fabric.CheckValuePropertyOperation" /> is generally used as a precondition for the write operations in the batch.</span></span> <span data-ttu-id="f7b40-104">Beachten Sie, dass, wenn mindestens eine <see cref="T:System.Fabric.PropertyBatchOperation" /> ein Fehler auftritt, der gesamte Batch schlägt fehl, und kann nicht übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="f7b40-104">Note that if one <see cref="T:System.Fabric.PropertyBatchOperation" /> fails, the entire batch fails and cannot be committed.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckValuePropertyOperation (string propertyName, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CheckValuePropertyOperation.#ctor(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Byte())" />
      <MemberSignature Language="F#" Value="new System.Fabric.CheckValuePropertyOperation : string * byte[] -&gt; System.Fabric.CheckValuePropertyOperation" Usage="new System.Fabric.CheckValuePropertyOperation (propertyName, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="f7b40-105">Der Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="f7b40-105">The name of the property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="f7b40-106">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="f7b40-106">The value of the property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f7b40-107">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.CheckValuePropertyOperation" /> -Klasse mit angegebenen <paramref name="propertyName" /> und <see cref="T:System.Byte" />[]-Wert.</span><span class="sxs-lookup"><span data-stu-id="f7b40-107">Initializes a new instance of the <see cref="T:System.Fabric.CheckValuePropertyOperation" /> class with specified <paramref name="propertyName" /> and <see cref="T:System.Byte" />[] value.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckValuePropertyOperation (string propertyName, double value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, float64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CheckValuePropertyOperation.#ctor(System.String,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Double)" />
      <MemberSignature Language="F#" Value="new System.Fabric.CheckValuePropertyOperation : string * double -&gt; System.Fabric.CheckValuePropertyOperation" Usage="new System.Fabric.CheckValuePropertyOperation (propertyName, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="f7b40-108">Der Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="f7b40-108">The name of the property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="f7b40-109">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="f7b40-109">The value of the property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f7b40-110">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.CheckValuePropertyOperation" /> -Klasse mit angegebenen <paramref name="propertyName" /> und <see cref="T:System.Double" /> Wert.</span><span class="sxs-lookup"><span data-stu-id="f7b40-110">Initializes a new instance of the <see cref="T:System.Fabric.CheckValuePropertyOperation" /> class with specified <paramref name="propertyName" /> and <see cref="T:System.Double" /> value.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckValuePropertyOperation (string propertyName, Guid value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, valuetype System.Guid value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CheckValuePropertyOperation.#ctor(System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Guid)" />
      <MemberSignature Language="F#" Value="new System.Fabric.CheckValuePropertyOperation : string * Guid -&gt; System.Fabric.CheckValuePropertyOperation" Usage="new System.Fabric.CheckValuePropertyOperation (propertyName, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="f7b40-111">Der Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="f7b40-111">The name of the property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="f7b40-112">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="f7b40-112">The value of the property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f7b40-113">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.CheckValuePropertyOperation" /> -Klasse mit angegebenen <paramref name="propertyName" /> und <see cref="T:System.Guid" /> Wert.</span><span class="sxs-lookup"><span data-stu-id="f7b40-113">Initializes a new instance of the <see cref="T:System.Fabric.CheckValuePropertyOperation" /> class with specified <paramref name="propertyName" /> and <see cref="T:System.Guid" /> value.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckValuePropertyOperation (string propertyName, long value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, int64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CheckValuePropertyOperation.#ctor(System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Long)" />
      <MemberSignature Language="F#" Value="new System.Fabric.CheckValuePropertyOperation : string * int64 -&gt; System.Fabric.CheckValuePropertyOperation" Usage="new System.Fabric.CheckValuePropertyOperation (propertyName, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="f7b40-114">Der Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="f7b40-114">The name of the property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="f7b40-115">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="f7b40-115">The value of the property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f7b40-116">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.CheckValuePropertyOperation" /> -Klasse mit angegebenen <paramref name="propertyName" /> und <see cref="T:System.Int64" /> Wert.</span><span class="sxs-lookup"><span data-stu-id="f7b40-116">Initializes a new instance of the <see cref="T:System.Fabric.CheckValuePropertyOperation" /> class with specified <paramref name="propertyName" /> and <see cref="T:System.Int64" /> value.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckValuePropertyOperation (string propertyName, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CheckValuePropertyOperation.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.CheckValuePropertyOperation : string * string -&gt; System.Fabric.CheckValuePropertyOperation" Usage="new System.Fabric.CheckValuePropertyOperation (propertyName, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="f7b40-117">Der Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="f7b40-117">The name of the property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="f7b40-118">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="f7b40-118">The value of the property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f7b40-119">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.CheckValuePropertyOperation" /> -Klasse mit angegebenen <paramref name="propertyName" /> und <see cref="T:System.String" /> Wert.</span><span class="sxs-lookup"><span data-stu-id="f7b40-119">Initializes a new instance of the <see cref="T:System.Fabric.CheckValuePropertyOperation" /> class with specified <paramref name="propertyName" /> and <see cref="T:System.String" /> value.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyType">
      <MemberSignature Language="C#" Value="public System.Fabric.PropertyTypeId PropertyType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PropertyTypeId PropertyType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CheckValuePropertyOperation.PropertyType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyType As PropertyTypeId" />
      <MemberSignature Language="F#" Value="member this.PropertyType : System.Fabric.PropertyTypeId" Usage="System.Fabric.CheckValuePropertyOperation.PropertyType" />
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
          <para><span data-ttu-id="f7b40-120">Ruft den Typ der Eigenschaft ab.</span><span class="sxs-lookup"><span data-stu-id="f7b40-120">Gets the type of the property.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="f7b40-121">Der Typ der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="f7b40-121">The type of the property.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyValue">
      <MemberSignature Language="C#" Value="public object PropertyValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object PropertyValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CheckValuePropertyOperation.PropertyValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyValue As Object" />
      <MemberSignature Language="F#" Value="member this.PropertyValue : obj" Usage="System.Fabric.CheckValuePropertyOperation.PropertyValue" />
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
          <para><span data-ttu-id="f7b40-122">Ruft den Wert der Eigenschaft ab.</span><span class="sxs-lookup"><span data-stu-id="f7b40-122">Gets the value of the property.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="f7b40-123">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="f7b40-123">The value of the property.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>