<Type Name="StreamWriterDelegate" FullName="Microsoft.ServiceBus.Web.StreamWriterDelegate">
  <TypeSignature Language="C#" Value="public delegate void StreamWriterDelegate(Stream output);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed StreamWriterDelegate extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Web.StreamWriterDelegate" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Sub StreamWriterDelegate(output As Stream)" />
  <TypeSignature Language="F#" Value="type StreamWriterDelegate = delegate of Stream -&gt; unit" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="output" Type="System.IO.Stream" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Void</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="output">Der Stream, der den Nachrichtentext zu schreiben.</param>
    <summary>Dieser Delegat StreamMessageHelper wird von der Text der per Streaming übertragenen Nachrichten schreiben.</summary>
    <remarks>To be added.</remarks>
  </Docs>
</Type>