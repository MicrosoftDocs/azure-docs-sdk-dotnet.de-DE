<Type Name="ShardKey" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey">
  <TypeSignature Language="C#" Value="public sealed class ShardKey : IComparable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey&gt;, IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ShardKey extends System.Object implements class System.IComparable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey&gt;, class System.IEquatable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ShardKey&#xA;Implements IComparable(Of ShardKey), IEquatable(Of ShardKey)" />
  <TypeSignature Language="F#" Value="type ShardKey = class&#xA;    interface IComparable&lt;ShardKey&gt;&#xA;    interface IEquatable&lt;ShardKey&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IComparable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="e1af4-101">Shard-Schlüsselwert.</span><span class="sxs-lookup"><span data-stu-id="e1af4-101">Shard key value.</span></span> <span data-ttu-id="e1af4-102">Umschließt den Typ und den Wert ein, und ermöglicht das Normalisierung/denormalisierung für die Serialisierung.</span><span class="sxs-lookup"><span data-stu-id="e1af4-102">Wraps the type and value and allows normalization/denormalization for serialization.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ShardKey (byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (value As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey : byte[] -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey value" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="e1af4-103">Eingabebytearrays.</span><span class="sxs-lookup"><span data-stu-id="e1af4-103">Input byte array.</span></span></param>
        <summary><span data-ttu-id="e1af4-104">Erstellt einen shardschlüssel mithilfe eines Bytearrays.</span><span class="sxs-lookup"><span data-stu-id="e1af4-104">Constructs a shard key using a byte array.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ShardKey (DateTime value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.#ctor(System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (value As DateTime)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey : DateTime -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey value" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="e1af4-105">DateTime-Eingabewert.</span><span class="sxs-lookup"><span data-stu-id="e1af4-105">Input DateTime.</span></span></param>
        <summary><span data-ttu-id="e1af4-106">Erstellt eine shardschlüssel mit DateTime-Wert.</span><span class="sxs-lookup"><span data-stu-id="e1af4-106">Constructs a shard key using DateTime value.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ShardKey (DateTimeOffset value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTimeOffset value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.#ctor(System.DateTimeOffset)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (value As DateTimeOffset)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey : DateTimeOffset -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey value" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="e1af4-107">Geben Sie "DateTimeOffset".</span><span class="sxs-lookup"><span data-stu-id="e1af4-107">Input DateTimeOffset.</span></span></param>
        <summary><span data-ttu-id="e1af4-108">Erstellt einen shardschlüssel, die mit "TimeSpan"-Wert an.</span><span class="sxs-lookup"><span data-stu-id="e1af4-108">Constructs a shard key using TimeSpan value.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ShardKey (Guid value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.#ctor(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (value As Guid)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey : Guid -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey value" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="e1af4-109">Eingabe-Guid.</span><span class="sxs-lookup"><span data-stu-id="e1af4-109">Input Guid.</span></span></param>
        <summary><span data-ttu-id="e1af4-110">Erstellt eine shardschlüssel mithilfe einer Guid.</span><span class="sxs-lookup"><span data-stu-id="e1af4-110">Constructs a shard key using a Guid.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ShardKey (int value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.#ctor(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (value As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey : int -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey value" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="e1af4-111">Eingabe 32-Bit-Ganzzahl.</span><span class="sxs-lookup"><span data-stu-id="e1af4-111">Input 32-bit integer.</span></span></param>
        <summary><span data-ttu-id="e1af4-112">Erstellt eine shardschlüssel mit 32-Bit-Ganzzahlwert.</span><span class="sxs-lookup"><span data-stu-id="e1af4-112">Constructs a shard key using 32-bit integer value.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ShardKey (long value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.#ctor(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (value As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey : int64 -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey value" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="e1af4-113">Eingabe 64-Bit-Ganzzahl.</span><span class="sxs-lookup"><span data-stu-id="e1af4-113">Input 64-bit integer.</span></span></param>
        <summary><span data-ttu-id="e1af4-114">Erstellt ein 64-Bit-Ganzzahlwert mit shardschlüssel an.</span><span class="sxs-lookup"><span data-stu-id="e1af4-114">Constructs a shard key using 64-bit integer value.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ShardKey (object value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.#ctor(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (value As Object)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey : obj -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey value" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="e1af4-115">Eingabeobjekt.</span><span class="sxs-lookup"><span data-stu-id="e1af4-115">Input object.</span></span></param>
        <summary><span data-ttu-id="e1af4-116">Erstellt das angegebene Objekt mit einen shardschlüssel an.</span><span class="sxs-lookup"><span data-stu-id="e1af4-116">Constructs a shard key using given object.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ShardKey (TimeSpan value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.#ctor(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (value As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey : TimeSpan -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey value" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="e1af4-117">TimeSpan-Eingabewert.</span><span class="sxs-lookup"><span data-stu-id="e1af4-117">Input TimeSpan.</span></span></param>
        <summary><span data-ttu-id="e1af4-118">Erstellt einen shardschlüssel, die mit "TimeSpan"-Wert an.</span><span class="sxs-lookup"><span data-stu-id="e1af4-118">Constructs a shard key using TimeSpan value.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ShardKey (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType keyType, object value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType keyType, object value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.#ctor(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyType As ShardKeyType, value As Object)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType * obj -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey (keyType, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyType" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType" />
        <Parameter Name="value" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="keyType"><span data-ttu-id="e1af4-119">Der Schlüsseltyp des Werts im-Objekt.</span><span class="sxs-lookup"><span data-stu-id="e1af4-119">The key type of value in object.</span></span></param>
        <param name="value"><span data-ttu-id="e1af4-120">Eingabeobjekt.</span><span class="sxs-lookup"><span data-stu-id="e1af4-120">Input object.</span></span></param>
        <summary>
            <span data-ttu-id="e1af4-121">Erstellt einen shardschlüssel, die mit den angegebenen Objekt und den "KeyType".</span><span class="sxs-lookup"><span data-stu-id="e1af4-121">Constructs a shard key using given object and keyType.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompareTo">
      <MemberSignature Language="C#" Value="public int CompareTo (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 CompareTo(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.CompareTo(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompareTo (other As ShardKey) As Integer" />
      <MemberSignature Language="F#" Value="abstract member CompareTo : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey -&gt; int&#xA;override this.CompareTo : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey -&gt; int" Usage="shardKey.CompareTo other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IComparable`1.CompareTo(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="e1af4-122">Die <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> mit diesem Objekt verglichen.</span><span class="sxs-lookup"><span data-stu-id="e1af4-122">The <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> compared with this object.</span></span></param>
        <summary>
            <span data-ttu-id="e1af4-123">Vergleicht zwei <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> Werte.</span><span class="sxs-lookup"><span data-stu-id="e1af4-123">Compares between two <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="e1af4-124">0 für gleich, &lt; 1, wenn dieser Schlüssel ist kleiner als <paramref name="other" />, &gt; andernfalls 1.</span><span class="sxs-lookup"><span data-stu-id="e1af4-124">0 for equality, &lt; -1 if this key is less than <paramref name="other" />, &gt; 1 otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataType">
      <MemberSignature Language="C#" Value="public Type DataType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type DataType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.DataType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataType As Type" />
      <MemberSignature Language="F#" Value="member this.DataType : Type" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.DataType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1af4-125">Ruft den Typ des Werts im Objekt vorhanden.</span><span class="sxs-lookup"><span data-stu-id="e1af4-125">Gets the type of the value present in the object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DetectShardKeyType">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType DetectShardKeyType (object value);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType DetectShardKeyType(object value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.DetectShardKeyType(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DetectShardKeyType (value As Object) As ShardKeyType" />
      <MemberSignature Language="F#" Value="static member DetectShardKeyType : obj -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.DetectShardKeyType value" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="e1af4-126">Angegebene Wert.</span><span class="sxs-lookup"><span data-stu-id="e1af4-126">Given value.</span></span> <span data-ttu-id="e1af4-127">Darf nicht Null sein.</span><span class="sxs-lookup"><span data-stu-id="e1af4-127">Must be non-null.</span></span></param>
        <summary>
            <span data-ttu-id="e1af4-128">Erkennen Sie seine ShardKeyType angegebene ein Objekt.</span><span class="sxs-lookup"><span data-stu-id="e1af4-128">Given an object detect its ShardKeyType.</span></span>
            </summary>
        <returns><span data-ttu-id="e1af4-129">Entsprechende ShardKeyType.</span><span class="sxs-lookup"><span data-stu-id="e1af4-129">Corresponding ShardKeyType.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.Equals(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As ShardKey) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey -&gt; bool" Usage="shardKey.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="e1af4-130">ShardKey für den Vergleich mit.</span><span class="sxs-lookup"><span data-stu-id="e1af4-130">ShardKey to compare with.</span></span></param>
        <summary>
            <span data-ttu-id="e1af4-131">Führt Vergleiche auf Gleichheit mit einem anderen ShardKey angegeben.</span><span class="sxs-lookup"><span data-stu-id="e1af4-131">Performs equality comparison with another given ShardKey.</span></span>
            </summary>
        <returns><span data-ttu-id="e1af4-132">True, wenn dieselbe shardschlüssel, "false" andernfalls.</span><span class="sxs-lookup"><span data-stu-id="e1af4-132">True if same shard key, false otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="shardKey.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="e1af4-133">Das Objekt, das mit dem aktuellen Objekt verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e1af4-133">The object to compare with the current object.</span></span></param>
        <summary>
            <span data-ttu-id="e1af4-134">Bestimmt, ob das angegebene Objekt mit dem aktuellen Objekt identisch ist.</span><span class="sxs-lookup"><span data-stu-id="e1af4-134">Determines whether the specified object is equal to the current object.</span></span>
            </summary>
        <returns><span data-ttu-id="e1af4-135">True, wenn das angegebene Objekt mit dem aktuellen Objekt identisch ist. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="e1af4-135">True if the specified object is equal to the current object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FromRawValue">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey FromRawValue (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType keyType, byte[] rawValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey FromRawValue(valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType keyType, unsigned int8[] rawValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.FromRawValue(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FromRawValue (keyType As ShardKeyType, rawValue As Byte()) As ShardKey" />
      <MemberSignature Language="F#" Value="static member FromRawValue : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType * byte[] -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.FromRawValue (keyType, rawValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyType" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType" />
        <Parameter Name="rawValue" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="keyType"><span data-ttu-id="e1af4-136">Typ des der shardschlüssel (Int32, Int64, Guid, Byte [] usw.).</span><span class="sxs-lookup"><span data-stu-id="e1af4-136">Type of the shard key (Int32, Int64, Guid, byte[] etc.).</span></span></param>
        <param name="rawValue"><span data-ttu-id="e1af4-137">Binäre Darstellung des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="e1af4-137">Binary representation of the key.</span></span></param>
        <summary>
            <span data-ttu-id="e1af4-138">Instanziiert einen neuen shardschlüssel mit dem angegebenen Typ und eine binäre Darstellung.</span><span class="sxs-lookup"><span data-stu-id="e1af4-138">Instantiates a new shard key using the specified type and binary representation.</span></span>
            </summary>
        <returns><span data-ttu-id="e1af4-139">Eine neue Schlüssel Shard-Instanz.</span><span class="sxs-lookup"><span data-stu-id="e1af4-139">A new shard key instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="shardKey.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e1af4-140">Berechnet den Hashcode für diese Instanz an.</span><span class="sxs-lookup"><span data-stu-id="e1af4-140">Calculates the hash code for this instance.</span></span>
            </summary>
        <returns><span data-ttu-id="e1af4-141">Der Hashcode für das Objekt.</span><span class="sxs-lookup"><span data-stu-id="e1af4-141">Hash code for the object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetValue&lt;T&gt;">
      <MemberSignature Language="C#" Value="public T GetValue&lt;T&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !!T GetValue&lt;T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.GetValue``1" />
      <MemberSignature Language="VB.NET" Value="Public Function GetValue(Of T) () As T" />
      <MemberSignature Language="F#" Value="member this.GetValue : unit -&gt; 'T" Usage="shardKey.GetValue " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T"><span data-ttu-id="e1af4-142">Der Typ des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="e1af4-142">Type of the key.</span></span></typeparam>
        <summary>
            <span data-ttu-id="e1af4-143">Ruft den stark typisierten Wert des Schlüssels Shard ab.</span><span class="sxs-lookup"><span data-stu-id="e1af4-143">Gets the strongly typed value of the shard key.</span></span>
            </summary>
        <returns><span data-ttu-id="e1af4-144">Der Wert des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="e1af4-144">Value of the key.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasValue">
      <MemberSignature Language="C#" Value="public bool HasValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.HasValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasValue As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasValue : bool" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.HasValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1af4-145">True, wenn der Schlüssel einen Wert hat. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="e1af4-145">True if the key has a value; otherwise, false.</span></span> <span data-ttu-id="e1af4-146">Plus unendlich zurückgegeben "false".</span><span class="sxs-lookup"><span data-stu-id="e1af4-146">Positive infinity returns false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsMax">
      <MemberSignature Language="C#" Value="public bool IsMax { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsMax" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.IsMax" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsMax As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsMax : bool" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.IsMax" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1af4-147">True, wenn der Schlüssel-Wert plus unendlich ist. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="e1af4-147">True if the key value is positive infinity; otherwise, false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsMin">
      <MemberSignature Language="C#" Value="public bool IsMin { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsMin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.IsMin" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsMin As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsMin : bool" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.IsMin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1af4-148">Gibt "true" zurück, wenn der Schlüsselwert minus unendlich ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="e1af4-148">Returns true if the key value is negative infinity; otherwise, false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSupportedType">
      <MemberSignature Language="C#" Value="public static bool IsSupportedType (Type type);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsSupportedType(class System.Type type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.IsSupportedType(System.Type)" />
      <MemberSignature Language="F#" Value="static member IsSupportedType : Type -&gt; bool" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.IsSupportedType type" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="type" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="type"><span data-ttu-id="e1af4-149">Typ der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="e1af4-149">Input type.</span></span></param>
        <summary>
            <span data-ttu-id="e1af4-150">Überprüft, ob der angegebene Typ als ShardKey Typ unterstützt wird.</span><span class="sxs-lookup"><span data-stu-id="e1af4-150">Checks whether the specified type is supported as ShardKey type.</span></span>
            </summary>
        <returns><span data-ttu-id="e1af4-151">"True", wenn unterstützt, "false" andernfalls.</span><span class="sxs-lookup"><span data-stu-id="e1af4-151">True if supported, false otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType KeyType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType KeyType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.KeyType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyType As ShardKeyType" />
      <MemberSignature Language="F#" Value="member this.KeyType : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.KeyType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1af4-152">Ruft den Typ der shardschlüssel ab.</span><span class="sxs-lookup"><span data-stu-id="e1af4-152">Gets the type of the shard key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Max">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey Max (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey left, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey Max(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey left, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey right) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.Max(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Max (left As ShardKey, right As ShardKey) As ShardKey" />
      <MemberSignature Language="F#" Value="static member Max : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.Max (left, right)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
        <Parameter Name="right" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
      </Parameters>
      <Docs>
        <param name="left"><span data-ttu-id="e1af4-153">Linken Seite.</span><span class="sxs-lookup"><span data-stu-id="e1af4-153">Left hand side.</span></span></param>
        <param name="right"><span data-ttu-id="e1af4-154">Rechts.</span><span class="sxs-lookup"><span data-stu-id="e1af4-154">Right hand side.</span></span></param>
        <summary>
            <span data-ttu-id="e1af4-155">Ruft das Maximum von zwei Shard Schlüssel ab.</span><span class="sxs-lookup"><span data-stu-id="e1af4-155">Gets the maximum of two shard keys.</span></span>
            </summary>
        <returns><span data-ttu-id="e1af4-156">Maximal zwei Shard-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="e1af4-156">Maximum of two shard keys.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBinary">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MaxBinary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MaxBinary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MaxBinary" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MaxBinary As ShardKey" />
      <MemberSignature Language="F#" Value="member this.MaxBinary : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MaxBinary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e1af4-157">Stellt minus unendlich dar.</span><span class="sxs-lookup"><span data-stu-id="e1af4-157">Represents negative infinity.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDateTime">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MaxDateTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MaxDateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MaxDateTime" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MaxDateTime As ShardKey" />
      <MemberSignature Language="F#" Value="member this.MaxDateTime : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MaxDateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e1af4-158">Stellt minus unendlich dar.</span><span class="sxs-lookup"><span data-stu-id="e1af4-158">Represents negative infinity.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDateTimeOffset">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MaxDateTimeOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MaxDateTimeOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MaxDateTimeOffset" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MaxDateTimeOffset As ShardKey" />
      <MemberSignature Language="F#" Value="member this.MaxDateTimeOffset : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MaxDateTimeOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e1af4-159">Stellt minus unendlich dar.</span><span class="sxs-lookup"><span data-stu-id="e1af4-159">Represents negative infinity.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxGuid">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MaxGuid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MaxGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MaxGuid" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MaxGuid As ShardKey" />
      <MemberSignature Language="F#" Value="member this.MaxGuid : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MaxGuid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e1af4-160">Stellt minus unendlich dar.</span><span class="sxs-lookup"><span data-stu-id="e1af4-160">Represents negative infinity.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxInt32">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MaxInt32 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MaxInt32" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MaxInt32" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MaxInt32 As ShardKey" />
      <MemberSignature Language="F#" Value="member this.MaxInt32 : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MaxInt32" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e1af4-161">Stellt minus unendlich dar.</span><span class="sxs-lookup"><span data-stu-id="e1af4-161">Represents negative infinity.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxInt64">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MaxInt64 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MaxInt64" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MaxInt64" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MaxInt64 As ShardKey" />
      <MemberSignature Language="F#" Value="member this.MaxInt64 : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MaxInt64" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e1af4-162">Stellt minus unendlich dar.</span><span class="sxs-lookup"><span data-stu-id="e1af4-162">Represents negative infinity.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTimeSpan">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MaxTimeSpan { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MaxTimeSpan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MaxTimeSpan" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MaxTimeSpan As ShardKey" />
      <MemberSignature Language="F#" Value="member this.MaxTimeSpan : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MaxTimeSpan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e1af4-163">Stellt minus unendlich dar.</span><span class="sxs-lookup"><span data-stu-id="e1af4-163">Represents negative infinity.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Min">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey Min (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey left, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey Min(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey left, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey right) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.Min(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Min (left As ShardKey, right As ShardKey) As ShardKey" />
      <MemberSignature Language="F#" Value="static member Min : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.Min (left, right)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
        <Parameter Name="right" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
      </Parameters>
      <Docs>
        <param name="left"><span data-ttu-id="e1af4-164">Linken Seite.</span><span class="sxs-lookup"><span data-stu-id="e1af4-164">Left hand side.</span></span></param>
        <param name="right"><span data-ttu-id="e1af4-165">Rechts.</span><span class="sxs-lookup"><span data-stu-id="e1af4-165">Right hand side.</span></span></param>
        <summary>
            <span data-ttu-id="e1af4-166">Ruft das Minimum von zwei Shard Schlüssel ab.</span><span class="sxs-lookup"><span data-stu-id="e1af4-166">Gets the minimum of two shard keys.</span></span>
            </summary>
        <returns><span data-ttu-id="e1af4-167">Mindestens zwei Shard-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="e1af4-167">Minimum of two shard keys.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinBinary">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MinBinary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MinBinary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MinBinary" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MinBinary As ShardKey" />
      <MemberSignature Language="F#" Value="member this.MinBinary : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MinBinary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e1af4-168">Stellt minus unendlich dar.</span><span class="sxs-lookup"><span data-stu-id="e1af4-168">Represents negative infinity.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinDateTime">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MinDateTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MinDateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MinDateTime" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MinDateTime As ShardKey" />
      <MemberSignature Language="F#" Value="member this.MinDateTime : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MinDateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e1af4-169">Stellt minus unendlich dar.</span><span class="sxs-lookup"><span data-stu-id="e1af4-169">Represents negative infinity.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinDateTimeOffset">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MinDateTimeOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MinDateTimeOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MinDateTimeOffset" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MinDateTimeOffset As ShardKey" />
      <MemberSignature Language="F#" Value="member this.MinDateTimeOffset : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MinDateTimeOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e1af4-170">Stellt minus unendlich dar.</span><span class="sxs-lookup"><span data-stu-id="e1af4-170">Represents negative infinity.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinGuid">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MinGuid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MinGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MinGuid" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MinGuid As ShardKey" />
      <MemberSignature Language="F#" Value="member this.MinGuid : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MinGuid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e1af4-171">Stellt minus unendlich dar.</span><span class="sxs-lookup"><span data-stu-id="e1af4-171">Represents negative infinity.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinInt32">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MinInt32 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MinInt32" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MinInt32" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MinInt32 As ShardKey" />
      <MemberSignature Language="F#" Value="member this.MinInt32 : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MinInt32" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e1af4-172">Stellt minus unendlich dar.</span><span class="sxs-lookup"><span data-stu-id="e1af4-172">Represents negative infinity.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinInt64">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MinInt64 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MinInt64" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MinInt64" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MinInt64 As ShardKey" />
      <MemberSignature Language="F#" Value="member this.MinInt64 : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MinInt64" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e1af4-173">Stellt minus unendlich dar.</span><span class="sxs-lookup"><span data-stu-id="e1af4-173">Represents negative infinity.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinTimeSpan">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MinTimeSpan { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey MinTimeSpan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MinTimeSpan" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MinTimeSpan As ShardKey" />
      <MemberSignature Language="F#" Value="member this.MinTimeSpan : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.MinTimeSpan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e1af4-174">Stellt minus unendlich dar.</span><span class="sxs-lookup"><span data-stu-id="e1af4-174">Represents negative infinity.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey left, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey left, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey right) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.op_Equality(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (left As ShardKey, right As ShardKey) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey -&gt; bool" Usage="left = right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
        <Parameter Name="right" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
      </Parameters>
      <Docs>
        <param name="left"><span data-ttu-id="e1af4-175">Links</span><span class="sxs-lookup"><span data-stu-id="e1af4-175">Left hand side</span></span></param>
        <param name="right"><span data-ttu-id="e1af4-176">Rechte Seite</span><span class="sxs-lookup"><span data-stu-id="e1af4-176">Right hand side</span></span></param>
        <summary>
            <span data-ttu-id="e1af4-177">Gleichheitsoperator.</span><span class="sxs-lookup"><span data-stu-id="e1af4-177">Equality operator.</span></span>
            </summary>
        <returns><span data-ttu-id="e1af4-178">True, wenn die beiden Objekte gleich sind, und "false" in allen anderen Fällen sind</span><span class="sxs-lookup"><span data-stu-id="e1af4-178">True if the two objects are equal, false in all other cases</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_GreaterThan">
      <MemberSignature Language="C#" Value="public static bool operator &gt; (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey left, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_GreaterThan(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey left, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey right) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.op_GreaterThan(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &gt; (left As ShardKey, right As ShardKey) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &gt; ) : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey -&gt; bool" Usage="left &gt; right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
        <Parameter Name="right" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
      </Parameters>
      <Docs>
        <param name="left"><span data-ttu-id="e1af4-179">Linken <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> des Operators.</span><span class="sxs-lookup"><span data-stu-id="e1af4-179">Left hand side <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> of the operator.</span></span></param>
        <param name="right"><span data-ttu-id="e1af4-180">Rechts <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> des Operators.</span><span class="sxs-lookup"><span data-stu-id="e1af4-180">Right hand side <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> of the operator.</span></span></param>
        <summary>
            <span data-ttu-id="e1af4-181">Vergleicht zwei <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> lexikografischen Reihenfolge (größer als) verwenden.</span><span class="sxs-lookup"><span data-stu-id="e1af4-181">Compares two <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> using lexicographic order (greater than).</span></span>
            </summary>
        <returns><span data-ttu-id="e1af4-182">True, wenn Lhs &gt; Rhs</span><span class="sxs-lookup"><span data-stu-id="e1af4-182">True if lhs &gt; rhs</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_GreaterThanOrEqual">
      <MemberSignature Language="C#" Value="public static bool operator &gt;= (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey left, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_GreaterThanOrEqual(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey left, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey right) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.op_GreaterThanOrEqual(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &gt;= (left As ShardKey, right As ShardKey) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &gt;= ) : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey -&gt; bool" Usage="left &gt;= right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
        <Parameter Name="right" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
      </Parameters>
      <Docs>
        <param name="left"><span data-ttu-id="e1af4-183">Linken <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> des Operators.</span><span class="sxs-lookup"><span data-stu-id="e1af4-183">Left hand side <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> of the operator.</span></span></param>
        <param name="right"><span data-ttu-id="e1af4-184">Rechts <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> des Operators.</span><span class="sxs-lookup"><span data-stu-id="e1af4-184">Right hand side <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> of the operator.</span></span></param>
        <summary>
            <span data-ttu-id="e1af4-185">Vergleicht zwei <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> mithilfe der lexikografischen Reihenfolge (größer oder gleich).</span><span class="sxs-lookup"><span data-stu-id="e1af4-185">Compares two <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> using lexicographic order (greater or equal).</span></span> 
            </summary>
        <returns><span data-ttu-id="e1af4-186">True, wenn Lhs &gt;= Rhs</span><span class="sxs-lookup"><span data-stu-id="e1af4-186">True if lhs &gt;= rhs</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey left, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey left, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey right) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.op_Inequality(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (left As ShardKey, right As ShardKey) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey -&gt; bool" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.op_Inequality (left, right)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
        <Parameter Name="right" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
      </Parameters>
      <Docs>
        <param name="left"><span data-ttu-id="e1af4-187">Links</span><span class="sxs-lookup"><span data-stu-id="e1af4-187">Left hand side</span></span></param>
        <param name="right"><span data-ttu-id="e1af4-188">Rechte Seite</span><span class="sxs-lookup"><span data-stu-id="e1af4-188">Right hand side</span></span></param>
        <summary>
            <span data-ttu-id="e1af4-189">Ungleichheitsoperator.</span><span class="sxs-lookup"><span data-stu-id="e1af4-189">Inequality operator.</span></span>
            </summary>
        <returns><span data-ttu-id="e1af4-190">True, wenn die beiden Objekte nicht gleich, in allen anderen Fällen "false"</span><span class="sxs-lookup"><span data-stu-id="e1af4-190">True if the two objects are not equal, false in all other cases</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_LessThan">
      <MemberSignature Language="C#" Value="public static bool operator &lt; (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey left, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_LessThan(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey left, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey right) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.op_LessThan(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &lt; (left As ShardKey, right As ShardKey) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &lt; ) : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey -&gt; bool" Usage="left &lt; right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
        <Parameter Name="right" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
      </Parameters>
      <Docs>
        <param name="left"><span data-ttu-id="e1af4-191">Linken <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> des Operators.</span><span class="sxs-lookup"><span data-stu-id="e1af4-191">Left hand side <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> of the operator.</span></span></param>
        <param name="right"><span data-ttu-id="e1af4-192">Rechts <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> des Operators.</span><span class="sxs-lookup"><span data-stu-id="e1af4-192">Right hand side <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> of the operator.</span></span></param>
        <summary>
            <span data-ttu-id="e1af4-193">Vergleicht zwei <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> mithilfe der lexikografischen Reihenfolge (kleiner als).</span><span class="sxs-lookup"><span data-stu-id="e1af4-193">Compares two <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> using lexicographic order (less than).</span></span>
            </summary>
        <returns><span data-ttu-id="e1af4-194">True, wenn Lhs &lt; Rhs</span><span class="sxs-lookup"><span data-stu-id="e1af4-194">True if lhs &lt; rhs</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_LessThanOrEqual">
      <MemberSignature Language="C#" Value="public static bool operator &lt;= (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey left, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_LessThanOrEqual(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey left, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey right) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.op_LessThanOrEqual(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &lt;= (left As ShardKey, right As ShardKey) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &lt;= ) : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey -&gt; bool" Usage="left &lt;= right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
        <Parameter Name="right" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
      </Parameters>
      <Docs>
        <param name="left"><span data-ttu-id="e1af4-195">Linken <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> des Operators.</span><span class="sxs-lookup"><span data-stu-id="e1af4-195">Left hand side <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> of the operator.</span></span></param>
        <param name="right"><span data-ttu-id="e1af4-196">Rechts <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> des Operators.</span><span class="sxs-lookup"><span data-stu-id="e1af4-196">Right hand side <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> of the operator.</span></span></param>
        <summary>
            <span data-ttu-id="e1af4-197">Vergleicht zwei <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> mithilfe der lexikografischen Reihenfolge (kleiner oder gleich).</span><span class="sxs-lookup"><span data-stu-id="e1af4-197">Compares two <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" /> using lexicographic order (less or equal).</span></span> 
            </summary>
        <returns><span data-ttu-id="e1af4-198">True, wenn Lhs &lt;= Rhs</span><span class="sxs-lookup"><span data-stu-id="e1af4-198">True if lhs &lt;= rhs</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RawValue">
      <MemberSignature Language="C#" Value="public byte[] RawValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] RawValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.RawValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RawValue As Byte()" />
      <MemberSignature Language="F#" Value="member this.RawValue : byte[]" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.RawValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Performance", "CA1819:PropertiesShouldNotReturnArrays", Justification="Necessary to return a copy of the byte array representing the key value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1af4-199">Ruft ein Bytearray, das den Schlüsselwert darstellt.</span><span class="sxs-lookup"><span data-stu-id="e1af4-199">Gets a byte array representing the key value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShardKeyTypeFromType">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType ShardKeyTypeFromType (Type type);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType ShardKeyTypeFromType(class System.Type type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.ShardKeyTypeFromType(System.Type)" />
      <MemberSignature Language="F#" Value="static member ShardKeyTypeFromType : Type -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.ShardKeyTypeFromType type" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="type" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="type"><span data-ttu-id="e1af4-200">CLR-Typ</span><span class="sxs-lookup"><span data-stu-id="e1af4-200">CLR type.</span></span></param>
        <summary>
            <span data-ttu-id="e1af4-201">Ruft die ShardKeyType, CLR-Typ entspricht.</span><span class="sxs-lookup"><span data-stu-id="e1af4-201">Gets the ShardKeyType corresponding to CLR type.</span></span>
            </summary>
        <returns><span data-ttu-id="e1af4-202">ShardKey-Typ.</span><span class="sxs-lookup"><span data-stu-id="e1af4-202">ShardKey type.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="shardKey.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e1af4-203">Konvertiert das Objekt in seine Zeichenfolgendarstellung.</span><span class="sxs-lookup"><span data-stu-id="e1af4-203">Converts the object to its string representation.</span></span>
            </summary>
        <returns><span data-ttu-id="e1af4-204">Entspricht der Zeichenfolgendarstellung des Objekts.</span><span class="sxs-lookup"><span data-stu-id="e1af4-204">String representation of the object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeFromShardKeyType">
      <MemberSignature Language="C#" Value="public static Type TypeFromShardKeyType (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType keyType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Type TypeFromShardKeyType(valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType keyType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.TypeFromShardKeyType(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TypeFromShardKeyType (keyType As ShardKeyType) As Type" />
      <MemberSignature Language="F#" Value="static member TypeFromShardKeyType : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType -&gt; Type" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.TypeFromShardKeyType keyType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyType" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType" />
      </Parameters>
      <Docs>
        <param name="keyType"><span data-ttu-id="e1af4-205">Geben Sie ein ShardKeyType.</span><span class="sxs-lookup"><span data-stu-id="e1af4-205">Input ShardKeyType.</span></span></param>
        <summary>
            <span data-ttu-id="e1af4-206">Ruft den CLR-Typ, der angegebenen ShardKeyType entspricht.</span><span class="sxs-lookup"><span data-stu-id="e1af4-206">Gets the CLR type corresponding to the specified ShardKeyType.</span></span>
            </summary>
        <returns><span data-ttu-id="e1af4-207">CLR-Typ</span><span class="sxs-lookup"><span data-stu-id="e1af4-207">CLR type.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public object Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As Object" />
      <MemberSignature Language="F#" Value="member this.Value : obj" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1721:PropertyNamesShouldNotMatchGetMethods", Justification="Necessary to return the un-typed value of the key")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1af4-208">Ruft den denormalisierten Wert des Schlüssels ab.</span><span class="sxs-lookup"><span data-stu-id="e1af4-208">Gets the denormalized value of the key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>