<Type Name="IStateSerializer&lt;T&gt;" FullName="Microsoft.ServiceFabric.Data.IStateSerializer&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IStateSerializer&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStateSerializer`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.IStateSerializer`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStateSerializer(Of T)" />
  <TypeSignature Language="F#" Value="type IStateSerializer&lt;'T&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T"><span data-ttu-id="ca333-101">Geben Sie zum Serialisieren und deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="ca333-101">Type to serialize and deserialize.</span></span></typeparam>
    <summary>
             <span data-ttu-id="ca333-102">Stellt ein benutzerdefiniertes Serialisierungsprogramm für den Typ <typeparamref name="T" />.</span><span class="sxs-lookup"><span data-stu-id="ca333-102">Represents a custom serializer for type <typeparamref name="T" />.</span></span>
             </summary>
    <remarks>
             <span data-ttu-id="ca333-103">Verwendung <see cref="M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer``1(Microsoft.ServiceFabric.Data.IStateSerializer{``0})" /> zum Registrieren eines benutzerdefinierten Serialisierers.</span><span class="sxs-lookup"><span data-stu-id="ca333-103">Use <see cref="M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer``1(Microsoft.ServiceFabric.Data.IStateSerializer{``0})" /> to register a custom serializer.</span></span>
             </remarks>
    <example>
             <span data-ttu-id="ca333-104">In diesem Beispiel Implementierung der Lese- und Schreibberechtigungen Überladungen rufen Sie einfach ihre Entsprechung Überladungen.</span><span class="sxs-lookup"><span data-stu-id="ca333-104">In this example, implementation of the Read and Write overloads simply call their counterpart overloads.</span></span>
             <span data-ttu-id="ca333-105">Die CurrentValue und BaseValue-Parameter werden von der Plattform nicht festgelegt und sollte ignoriert werden.</span><span class="sxs-lookup"><span data-stu-id="ca333-105">The currentValue and baseValue parameters are not set by the platform and should be ignored.</span></span>
             <code>
             class Order
             {
                 public byte Warehouse { get; set; }
                 public short District { get; set; }
                 public int Customer { get; set; }
                 public long OrderNumber { get; set; }
             }
            
             class OrderSerializer : IStateSerializer&lt;Order&gt;
             {
                 void Write(Order value, BinaryWriter writer)
                 {
                     writer.Write(value.Warehouse);
                     writer.Write(value.District);
                     writer.Write(value.Customer);
                     writer.Write(value.OrderNumber);
                 }
            
                 Order Read(BinaryReader reader)
                 {
                     Order value = new Order();
            
                     value.Warehouse = reader.ReadByte();
                     value.District = reader.ReadInt16();
                     value.Customer = reader.ReadInt32();
                     value.OrderNumber = reader.ReadInt64();
            
                     return value;
                 }
            
                 void Write(Order currentValue, Order newValue, BinaryWriter writer)
                 {
                     this.Write(newValue, writer);
                 }
            
                 Order Read(Order baseValue, BinaryReader reader)
                 {
                     return this.Read(reader);
                 }
             }
             </code></example>
  </Docs>
  <Members>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public T Read (System.IO.BinaryReader binaryReader);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Read(class System.IO.BinaryReader binaryReader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateSerializer`1.Read(System.IO.BinaryReader)" />
      <MemberSignature Language="F#" Value="abstract member Read : System.IO.BinaryReader -&gt; 'T" Usage="iStateSerializer.Read binaryReader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="binaryReader" Type="System.IO.BinaryReader" />
      </Parameters>
      <Docs>
        <param name="binaryReader"><span data-ttu-id="ca333-106">Die <see cref="T:System.IO.BinaryReader" /> aus zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="ca333-106">The <see cref="T:System.IO.BinaryReader" /> to deserialize from.</span></span></param>
        <summary>
            <span data-ttu-id="ca333-107">Deserialisiert aus der angegebenen <see cref="T:System.IO.BinaryReader" /> auf <typeparamref name="T" />.</span><span class="sxs-lookup"><span data-stu-id="ca333-107">Deserializes from the given <see cref="T:System.IO.BinaryReader" /> to <typeparamref name="T" />.</span></span>
            </summary>
        <returns><span data-ttu-id="ca333-108">Der deserialisierte Wert.</span><span class="sxs-lookup"><span data-stu-id="ca333-108">The deserialized value.</span></span></returns>
        <remarks>
            <span data-ttu-id="ca333-109">Beim Zugriff auf die <see cref="T:System.IO.BinaryReader" /> basisdatenstrom, muss darauf geachtet werden, wenn die Position im Stream verschoben.</span><span class="sxs-lookup"><span data-stu-id="ca333-109">When accessing the <see cref="T:System.IO.BinaryReader" /> base stream, care must be taken when moving the position in the stream.</span></span>
            <span data-ttu-id="ca333-110">Lesen muss auf die aktuelle Streamposition beginnen und enden an der aktuellen Position plus die Länge der Daten.</span><span class="sxs-lookup"><span data-stu-id="ca333-110">Reading must begin at the current stream position and end at the current position plus the length of your data.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public T Read (T baseValue, System.IO.BinaryReader binaryReader);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Read(!T baseValue, class System.IO.BinaryReader binaryReader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateSerializer`1.Read(`0,System.IO.BinaryReader)" />
      <MemberSignature Language="F#" Value="abstract member Read : 'T * System.IO.BinaryReader -&gt; 'T" Usage="iStateSerializer.Read (baseValue, binaryReader)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="baseValue" Type="T" />
        <Parameter Name="binaryReader" Type="System.IO.BinaryReader" />
      </Parameters>
      <Docs>
        <param name="baseValue"><span data-ttu-id="ca333-111">Preis für die Deserialisierung.</span><span class="sxs-lookup"><span data-stu-id="ca333-111">The base value for the deserialization.</span></span></param>
        <param name="binaryReader"><span data-ttu-id="ca333-112">Die <see cref="T:System.IO.BinaryReader" /> aus zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="ca333-112">The <see cref="T:System.IO.BinaryReader" /> to deserialize from.</span></span></param>
        <summary>
            <span data-ttu-id="ca333-113">Deserialisiert aus der angegebenen <see cref="T:System.IO.BinaryReader" /> auf <typeparamref name="T" />.</span><span class="sxs-lookup"><span data-stu-id="ca333-113">Deserializes from the given <see cref="T:System.IO.BinaryReader" /> to <typeparamref name="T" />.</span></span>
            </summary>
        <returns><span data-ttu-id="ca333-114">Der deserialisierte Wert.</span><span class="sxs-lookup"><span data-stu-id="ca333-114">The deserialized value.</span></span></returns>
        <remarks>
            <span data-ttu-id="ca333-115">Beim Zugriff auf die <see cref="T:System.IO.BinaryReader" /> basisdatenstrom, muss darauf geachtet werden, wenn die Position im Stream verschoben.</span><span class="sxs-lookup"><span data-stu-id="ca333-115">When accessing the <see cref="T:System.IO.BinaryReader" /> base stream, care must be taken when moving the position in the stream.</span></span>
            <span data-ttu-id="ca333-116">Lesen muss auf die aktuelle Streamposition beginnen und enden an der aktuellen Position plus die Länge der Daten.</span><span class="sxs-lookup"><span data-stu-id="ca333-116">Reading must begin at the current stream position and end at the current position plus the length of your data.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public void Write (T value, System.IO.BinaryWriter binaryWriter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Write(!T value, class System.IO.BinaryWriter binaryWriter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateSerializer`1.Write(`0,System.IO.BinaryWriter)" />
      <MemberSignature Language="F#" Value="abstract member Write : 'T * System.IO.BinaryWriter -&gt; unit" Usage="iStateSerializer.Write (value, binaryWriter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value" Type="T" />
        <Parameter Name="binaryWriter" Type="System.IO.BinaryWriter" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="ca333-117">Der zu serialisierende Wert.</span><span class="sxs-lookup"><span data-stu-id="ca333-117">The value to serialize.</span></span></param>
        <param name="binaryWriter"><span data-ttu-id="ca333-118">Die <see cref="T:System.IO.BinaryWriter" /> zu serialisieren.</span><span class="sxs-lookup"><span data-stu-id="ca333-118">The <see cref="T:System.IO.BinaryWriter" /> to serialize to.</span></span></param>
        <summary>
            <span data-ttu-id="ca333-119">Serialisiert einen Wert und schreibt ihn auf den angegebenen <see cref="T:System.IO.BinaryWriter" />.</span><span class="sxs-lookup"><span data-stu-id="ca333-119">Serializes a value and writes it to the given <see cref="T:System.IO.BinaryWriter" />.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="ca333-120">Beim Zugriff auf die <see cref="T:System.IO.BinaryWriter" /> basisdatenstrom, muss darauf geachtet werden, wenn die Position im Stream verschoben.</span><span class="sxs-lookup"><span data-stu-id="ca333-120">When accessing the <see cref="T:System.IO.BinaryWriter" /> base stream, care must be taken when moving the position in the stream.</span></span>
            <span data-ttu-id="ca333-121">Schreiben von muss auf die aktuelle Streamposition beginnen und enden an der aktuellen Position plus die Länge der Daten.</span><span class="sxs-lookup"><span data-stu-id="ca333-121">Writing must begin at the current stream position and end at the current position plus the length of your data.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public void Write (T baseValue, T targetValue, System.IO.BinaryWriter binaryWriter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Write(!T baseValue, !T targetValue, class System.IO.BinaryWriter binaryWriter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateSerializer`1.Write(`0,`0,System.IO.BinaryWriter)" />
      <MemberSignature Language="F#" Value="abstract member Write : 'T * 'T * System.IO.BinaryWriter -&gt; unit" Usage="iStateSerializer.Write (baseValue, targetValue, binaryWriter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="baseValue" Type="T" />
        <Parameter Name="targetValue" Type="T" />
        <Parameter Name="binaryWriter" Type="System.IO.BinaryWriter" />
      </Parameters>
      <Docs>
        <param name="baseValue"><span data-ttu-id="ca333-122">Preis für die Serialisierung.</span><span class="sxs-lookup"><span data-stu-id="ca333-122">The base value for the serialization.</span></span></param>
        <param name="targetValue"><span data-ttu-id="ca333-123">Der zu serialisierende Wert.</span><span class="sxs-lookup"><span data-stu-id="ca333-123">The value to serialize.</span></span></param>
        <param name="binaryWriter"><span data-ttu-id="ca333-124">Die <see cref="T:System.IO.BinaryWriter" /> zu serialisieren.</span><span class="sxs-lookup"><span data-stu-id="ca333-124">The <see cref="T:System.IO.BinaryWriter" /> to serialize to.</span></span></param>
        <summary>
            <span data-ttu-id="ca333-125">Serialisiert ein Objekt und schreibt es an der angegebenen <see cref="T:System.IO.BinaryWriter" />.</span><span class="sxs-lookup"><span data-stu-id="ca333-125">Serializes an object and writes it to the given <see cref="T:System.IO.BinaryWriter" />.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="ca333-126">Beim Zugriff auf die <see cref="T:System.IO.BinaryWriter" /> basisdatenstrom, muss darauf geachtet werden, wenn die Position im Stream verschoben.</span><span class="sxs-lookup"><span data-stu-id="ca333-126">When accessing the <see cref="T:System.IO.BinaryWriter" /> base stream, care must be taken when moving the position in the stream.</span></span>
            <span data-ttu-id="ca333-127">Schreiben von muss auf die aktuelle Streamposition beginnen und enden an der aktuellen Position plus die Länge der Daten.</span><span class="sxs-lookup"><span data-stu-id="ca333-127">Writing must begin at the current stream position and end at the current position plus the length of your data.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>