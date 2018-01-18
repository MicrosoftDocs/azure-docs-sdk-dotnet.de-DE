<Type Name="IncomingMessageBody" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IncomingMessageBody">
  <TypeSignature Language="C#" Value="public sealed class IncomingMessageBody : IDisposable, Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IMessageBody" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit IncomingMessageBody extends System.Object implements class Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IMessageBody, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IncomingMessageBody" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class IncomingMessageBody&#xA;Implements IDisposable, IMessageBody" />
  <TypeSignature Language="F#" Value="type IncomingMessageBody = class&#xA;    interface IMessageBody&#xA;    interface IDisposable" />
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
            <span data-ttu-id="960ae-101">Serialisierte Nachrichtentext aus einer eingehenden Verbindung empfangen.</span><span class="sxs-lookup"><span data-stu-id="960ae-101">Serialized Message Body received from an incoming connection.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IncomingMessageBody (System.IO.Stream receivedBufferStream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream receivedBufferStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IncomingMessageBody.#ctor(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (receivedBufferStream As Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IncomingMessageBody : System.IO.Stream -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IncomingMessageBody" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IncomingMessageBody receivedBufferStream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="receivedBufferStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="receivedBufferStream"></param>
        <summary>
            <span data-ttu-id="960ae-102">Erstellt eine eingehende Nachrichtentext mit dem empfangenen Datenstrom.</span><span class="sxs-lookup"><span data-stu-id="960ae-102">Creates an incoming Message Body with the received stream .</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IncomingMessageBody.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="incomingMessageBody.Dispose " />
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
            <span data-ttu-id="960ae-103">Die empfangene Pufferstream Dispose</span><span class="sxs-lookup"><span data-stu-id="960ae-103">Dispose the Received Buffer stream</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReceivedBuffer">
      <MemberSignature Language="C#" Value="public System.IO.Stream GetReceivedBuffer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.IO.Stream GetReceivedBuffer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IncomingMessageBody.GetReceivedBuffer" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReceivedBuffer () As Stream" />
      <MemberSignature Language="F#" Value="abstract member GetReceivedBuffer : unit -&gt; System.IO.Stream&#xA;override this.GetReceivedBuffer : unit -&gt; System.IO.Stream" Usage="incomingMessageBody.GetReceivedBuffer " />
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
            <span data-ttu-id="960ae-104">Zurückgeben der empfangenen Pufferstream</span><span class="sxs-lookup"><span data-stu-id="960ae-104">Return the Received Buffer Stream</span></span> 
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSendBuffers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;ArraySegment&lt;byte&gt;&gt; GetSendBuffers ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; GetSendBuffers() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IncomingMessageBody.GetSendBuffers" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSendBuffers () As IEnumerable(Of ArraySegment(Of Byte))" />
      <MemberSignature Language="F#" Value="abstract member GetSendBuffers : unit -&gt; seq&lt;ArraySegment&lt;byte&gt;&gt;&#xA;override this.GetSendBuffers : unit -&gt; seq&lt;ArraySegment&lt;byte&gt;&gt;" Usage="incomingMessageBody.GetSendBuffers " />
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
            <span data-ttu-id="960ae-105">Dies wird nicht für diese Implementierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="960ae-105">This is not used for this implementation</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>