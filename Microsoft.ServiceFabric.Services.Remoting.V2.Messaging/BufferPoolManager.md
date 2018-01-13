<Type Name="BufferPoolManager" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.BufferPoolManager">
  <TypeSignature Language="C#" Value="public sealed class BufferPoolManager : Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IBufferPoolManager" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BufferPoolManager extends System.Object implements class Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IBufferPoolManager" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.BufferPoolManager" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BufferPoolManager&#xA;Implements IBufferPoolManager" />
  <TypeSignature Language="F#" Value="type BufferPoolManager = class&#xA;    interface IBufferPoolManager" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IBufferPoolManager</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Mit der BufferManager-Klasse können Sie einen Pufferpool verwalten. Der Pool wird erstellt, wenn Sie diese Klasse instanziieren. Puffer wird instanziiert, wenn keine nicht verwendeten Puffer im Pool vorhanden sind.
            Zerstört, wenn der Pufferpool durch die Garbagecollection wieder zugänglich gemacht wird. Wenn Sie einen Puffer verwenden möchten, können Sie einen aus dem Pool nehmen und nach Abschluss der Arbeit wieder im Pool ablegen. Dieser Vorgang ist wesentlich schneller, als jedes Mal, wenn Sie einen Puffer benötigen, eine neuen zu erstellen und wieder zu zerstören.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BufferPoolManager (int segmentSize = 4096, int bufferLimit = 100);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 segmentSize, int32 bufferLimit) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.BufferPoolManager.#ctor(System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional segmentSize As Integer = 4096, Optional bufferLimit As Integer = 100)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.BufferPoolManager : int * int -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.BufferPoolManager" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.BufferPoolManager (segmentSize, bufferLimit)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="segmentSize" Type="System.Int32" />
        <Parameter Name="bufferLimit" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="segmentSize"></param>
        <param name="bufferLimit"></param>
        <summary>
            Initialisiert eine neue Instanz der BufferPoolManager-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnBuffer">
      <MemberSignature Language="C#" Value="public bool ReturnBuffer (Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer buffer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ReturnBuffer(class Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer buffer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.BufferPoolManager.ReturnBuffer(Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReturnBuffer (buffer As IPooledBuffer) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member ReturnBuffer : Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer -&gt; bool&#xA;override this.ReturnBuffer : Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer -&gt; bool" Usage="bufferPoolManager.ReturnBuffer buffer" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IBufferPoolManager.ReturnBuffer(Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer" />
      </Parameters>
      <Docs>
        <param name="buffer"></param>
        <summary>
            Gibt einen Puffer an den Pool zurück.
            Wenn der Grenzwert überschreitet, wird nicht Puffer an den Pool zurückgegeben.
            Es "false" zurückgeben, wenn der Puffer nicht zurückgegeben wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TakeBuffer">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer TakeBuffer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer TakeBuffer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.BufferPoolManager.TakeBuffer" />
      <MemberSignature Language="VB.NET" Value="Public Function TakeBuffer () As IPooledBuffer" />
      <MemberSignature Language="F#" Value="abstract member TakeBuffer : unit -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer&#xA;override this.TakeBuffer : unit -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer" Usage="bufferPoolManager.TakeBuffer " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IBufferPoolManager.TakeBuffer</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft einen Puffer aus dem Pool ab.
            Wenn sie alle nicht verwendeten Puffers nicht findet, instanziiert es neuen Puffer.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>