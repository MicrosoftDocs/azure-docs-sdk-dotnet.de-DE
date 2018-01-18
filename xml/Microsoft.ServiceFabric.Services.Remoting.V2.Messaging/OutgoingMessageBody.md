<Type Name="OutgoingMessageBody" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody">
  <TypeSignature Language="C#" Value="public sealed class OutgoingMessageBody : IDisposable, Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IMessageBody" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit OutgoingMessageBody extends System.Object implements class Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IMessageBody, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class OutgoingMessageBody&#xA;Implements IDisposable, IMessageBody" />
  <TypeSignature Language="F#" Value="type OutgoingMessageBody = class&#xA;    interface IMessageBody&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IMessageBody</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="ca5a9-101">Stellt den Nachrichtentext der ausgehenden unverschlüsselt gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="ca5a9-101">Represents the outgoing message body to be sent over the wire.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutgoingMessageBody (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer&gt; outgoingPooledBodyBuffers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer&gt; outgoingPooledBodyBuffers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody.#ctor(System.Collections.Generic.IEnumerable{Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (outgoingPooledBodyBuffers As IEnumerable(Of IPooledBuffer))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody : seq&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer&gt; -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody outgoingPooledBodyBuffers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="outgoingPooledBodyBuffers" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer&gt;" />
      </Parameters>
      <Docs>
        <param name="outgoingPooledBodyBuffers"></param>
        <summary>
            <span data-ttu-id="ca5a9-102">Erstellt von OutgoingMessageBody mit Liste der in einem Pool zusammengefasste Puffer</span><span class="sxs-lookup"><span data-stu-id="ca5a9-102">Creates OutgoingMessageBody with list of pooled Buffers</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutgoingMessageBody (System.Collections.Generic.IEnumerable&lt;ArraySegment&lt;byte&gt;&gt; outgoingBodyBuffers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; outgoingBodyBuffers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody.#ctor(System.Collections.Generic.IEnumerable{System.ArraySegment{System.Byte}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (outgoingBodyBuffers As IEnumerable(Of ArraySegment(Of Byte)))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody : seq&lt;ArraySegment&lt;byte&gt;&gt; -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody outgoingBodyBuffers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="outgoingBodyBuffers" Type="System.Collections.Generic.IEnumerable&lt;System.ArraySegment&lt;System.Byte&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="outgoingBodyBuffers">To be added.</param>
        <summary>
            <span data-ttu-id="ca5a9-103">Liste der Segmente erstellt OutgoingMessageBody.</span><span class="sxs-lookup"><span data-stu-id="ca5a9-103">Creates OutgoingMessageBody with list of segments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="outgoingMessageBody.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ca5a9-104">Lassen Sie die Puffer im Pool zusammengefasste, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="ca5a9-104">Release the pooled Buffers if it has any.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReceivedBuffer">
      <MemberSignature Language="C#" Value="public System.IO.Stream GetReceivedBuffer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.IO.Stream GetReceivedBuffer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody.GetReceivedBuffer" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReceivedBuffer () As Stream" />
      <MemberSignature Language="F#" Value="abstract member GetReceivedBuffer : unit -&gt; System.IO.Stream&#xA;override this.GetReceivedBuffer : unit -&gt; System.IO.Stream" Usage="outgoingMessageBody.GetReceivedBuffer " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IMessageBody.GetReceivedBuffer</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ca5a9-105">Diese Methode ist nicht implementiert.</span><span class="sxs-lookup"><span data-stu-id="ca5a9-105">This method is not implemented.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSendBuffers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;ArraySegment&lt;byte&gt;&gt; GetSendBuffers ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; GetSendBuffers() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody.GetSendBuffers" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSendBuffers () As IEnumerable(Of ArraySegment(Of Byte))" />
      <MemberSignature Language="F#" Value="abstract member GetSendBuffers : unit -&gt; seq&lt;ArraySegment&lt;byte&gt;&gt;&#xA;override this.GetSendBuffers : unit -&gt; seq&lt;ArraySegment&lt;byte&gt;&gt;" Usage="outgoingMessageBody.GetSendBuffers " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IMessageBody.GetSendBuffers</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.ArraySegment&lt;System.Byte&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ca5a9-106">Gibt den Puffern, die über das Netz gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="ca5a9-106">Returns the Buffers to be sent over the wire.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>