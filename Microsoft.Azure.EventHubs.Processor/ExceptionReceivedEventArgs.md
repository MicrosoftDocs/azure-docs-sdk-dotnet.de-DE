<Type Name="ExceptionReceivedEventArgs" FullName="Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs">
  <TypeSignature Language="C#" Value="public sealed class ExceptionReceivedEventArgs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ExceptionReceivedEventArgs extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ExceptionReceivedEventArgs" />
  <TypeSignature Language="F#" Value="type ExceptionReceivedEventArgs = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt Daten für das <see cref="M:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.NotifyOfException(System.String,System.String,System.Exception,System.String)" />-Ereignis bereit.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public string Action { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs.Action" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Action As String" />
      <MemberSignature Language="F#" Value="member this.Action : string" Usage="Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Eine kurze Zeichenfolge, die angibt, welche allgemeine Aktivitäten die Ausnahme ausgelöst hat.
            Eine Liste der möglichen Werte finden Sie in der EventProcessorHostActionString.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs.Exception" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception" Usage="Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die ausgelöste Ausnahme.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Hostname">
      <MemberSignature Language="C#" Value="public string Hostname { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Hostname" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs.Hostname" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Hostname As String" />
      <MemberSignature Language="F#" Value="member this.Hostname : string" Usage="Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs.Hostname" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermöglicht die Fehlerquelle zu unterscheiden, wenn mehrere in einem einzelnen Prozess hostet.
            </summary>
        <value>Der Name des Hosts, der die Ausnahme aufgetreten ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermöglicht die Fehlerquelle zu unterscheiden, wenn mehrere in einem einzelnen Prozess hostet.
            </summary>
        <value>Die Partitions-Id, die die Ausnahme aufgetreten ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>