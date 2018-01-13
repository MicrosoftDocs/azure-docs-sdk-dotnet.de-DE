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
            Eine Schnittstelle, die Clients ermöglicht, auf einen Puffer-Manager für einem bestimmten Dienstclient bereitzustellen. Diese Schnittstelle Standardressource der <see href="http://msdn.microsoft.com/en-us/library/system.servicemodel.channels.buffermanager.aspx">System.ServiceModel.Channels.BufferManager</see> Klasse.
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
            Ruft die Größe der durch den angegebenen Pool verwalteten Puffer in Byte ab. Beachten Sie, dass der Puffer-Manager muss Puffer, der die genaue Größe, die vom Client angeforderte zurückgeben.
            </summary>
        <returns>Die Größe der durch den angegebenen Pool verwalteten Puffer in Byte.</returns>
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
        <param name="buffer">Ein Bytearray, das Angeben des Puffers, an den Pool zurückzugeben.</param>
        <summary>
            Gibt einen Puffer an den Pool zurück.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Die pufferreferenz kann nicht null sein.</exception>
        <exception cref="T:System.ArgumentException">Länge des Puffers entspricht nicht dem Pool Puffer Length-Eigenschaft.</exception>
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
        <param name="bufferSize">Die Größe des angeforderten Puffers in Byte.</param>
        <summary>
            Ruft einen Puffer der angegebenen Größe oder größer aus dem Pool ab.
            </summary>
        <returns>Ein Bytearray, das der angeforderten Größe des Puffers entspricht.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Der angegebene Wert für <paramref name="bufferSize" /> darf nicht kleiner als 0 (null).</exception>
      </Docs>
    </Member>
  </Members>
</Type>