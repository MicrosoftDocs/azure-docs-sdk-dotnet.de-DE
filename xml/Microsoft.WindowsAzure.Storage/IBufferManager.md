<Type Name="IBufferManager" FullName="Microsoft.WindowsAzure.Storage.IBufferManager">
  <TypeSignature Language="C#" Value="public interface IBufferManager" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBufferManager" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.IBufferManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBufferManager" />
  <TypeSignature Language="F#" Value="type IBufferManager = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="66412-101">Eine Schnittstelle, die Clients ermöglicht, auf einen Puffer-Manager für einem bestimmten Dienstclient bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="66412-101">An interface that allows clients to provide a buffer manager to a given service client.</span></span> <span data-ttu-id="66412-102">Diese Schnittstelle Standardressource der <see href="http://msdn.microsoft.com/en-us/library/system.servicemodel.channels.buffermanager.aspx">System.ServiceModel.Channels.BufferManager</see> Klasse.</span><span class="sxs-lookup"><span data-stu-id="66412-102">This interface is patterned after the <see href="http://msdn.microsoft.com/en-us/library/system.servicemodel.channels.buffermanager.aspx">System.ServiceModel.Channels.BufferManager</see> class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetDefaultBufferSize">
      <MemberSignature Language="C#" Value="public int GetDefaultBufferSize ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 GetDefaultBufferSize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.IBufferManager.GetDefaultBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDefaultBufferSize () As Integer" />
      <MemberSignature Language="F#" Value="abstract member GetDefaultBufferSize : unit -&gt; int" Usage="iBufferManager.GetDefaultBufferSize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="66412-103">Ruft die Größe der durch den angegebenen Pool verwalteten Puffer in Byte ab.</span><span class="sxs-lookup"><span data-stu-id="66412-103">Gets the size, in bytes, of the buffers managed by the given pool.</span></span> <span data-ttu-id="66412-104">Beachten Sie, dass der Puffer-Manager muss Puffer, der die genaue Größe, die vom Client angeforderte zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="66412-104">Note that the buffer manager must return buffers of the exact size requested by the client.</span></span>
            </summary>
        <returns><span data-ttu-id="66412-105">Die Größe der durch den angegebenen Pool verwalteten Puffer in Byte.</span><span class="sxs-lookup"><span data-stu-id="66412-105">The size, in bytes, of the buffers managed by the given pool.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnBuffer">
      <MemberSignature Language="C#" Value="public void ReturnBuffer (byte[] buffer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReturnBuffer(unsigned int8[] buffer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.IBufferManager.ReturnBuffer(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReturnBuffer (buffer As Byte())" />
      <MemberSignature Language="F#" Value="abstract member ReturnBuffer : byte[] -&gt; unit" Usage="iBufferManager.ReturnBuffer buffer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="66412-106">Ein Bytearray, das Angeben des Puffers, an den Pool zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="66412-106">A byte array specifying the buffer to return to the pool.</span></span></param>
        <summary>
            <span data-ttu-id="66412-107">Gibt einen Puffer an den Pool zurück.</span><span class="sxs-lookup"><span data-stu-id="66412-107">Returns a buffer to the pool.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="66412-108">Die pufferreferenz kann nicht null sein.</span><span class="sxs-lookup"><span data-stu-id="66412-108">Buffer reference cannot be null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="66412-109">Länge des Puffers entspricht nicht dem Pool Puffer Length-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="66412-109">Length of buffer does not match the pool's buffer length property.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TakeBuffer">
      <MemberSignature Language="C#" Value="public byte[] TakeBuffer (int bufferSize);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance unsigned int8[] TakeBuffer(int32 bufferSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.IBufferManager.TakeBuffer(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function TakeBuffer (bufferSize As Integer) As Byte()" />
      <MemberSignature Language="F#" Value="abstract member TakeBuffer : int -&gt; byte[]" Usage="iBufferManager.TakeBuffer bufferSize" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="bufferSize" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="bufferSize"><span data-ttu-id="66412-110">Die Größe des angeforderten Puffers in Byte.</span><span class="sxs-lookup"><span data-stu-id="66412-110">The size, in bytes, of the requested buffer.</span></span></param>
        <summary>
            <span data-ttu-id="66412-111">Ruft einen Puffer der angegebenen Größe oder größer aus dem Pool ab.</span><span class="sxs-lookup"><span data-stu-id="66412-111">Gets a buffer of the specified size or larger from the pool.</span></span>
            </summary>
        <returns><span data-ttu-id="66412-112">Ein Bytearray, das der angeforderten Größe des Puffers entspricht.</span><span class="sxs-lookup"><span data-stu-id="66412-112">A byte array that is the requested size of the buffer.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="66412-113">Der angegebene Wert für <paramref name="bufferSize" /> darf nicht kleiner als 0 (null).</span><span class="sxs-lookup"><span data-stu-id="66412-113">The value specified for <paramref name="bufferSize" /> cannot be less than zero.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>