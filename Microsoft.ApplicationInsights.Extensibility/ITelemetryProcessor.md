<Type Name="ITelemetryProcessor" FullName="Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor">
  <TypeSignature Language="C#" Value="public interface ITelemetryProcessor" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITelemetryProcessor" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITelemetryProcessor" />
  <TypeSignature Language="F#" Value="type ITelemetryProcessor = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Stellt ein Objekt, das zum Verarbeiten von Telemetriedaten, die als Teil der an Application Insights senden verwendet.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Process">
      <MemberSignature Language="C#" Value="public void Process (Microsoft.ApplicationInsights.Channel.ITelemetry item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Process(class Microsoft.ApplicationInsights.Channel.ITelemetry item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor.Process(Microsoft.ApplicationInsights.Channel.ITelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Process (item As ITelemetry)" />
      <MemberSignature Language="F#" Value="abstract member Process : Microsoft.ApplicationInsights.Channel.ITelemetry -&gt; unit" Usage="iTelemetryProcessor.Process item" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.ApplicationInsights.Channel.ITelemetry" />
      </Parameters>
      <Docs>
        <param name="item">Ein gesammelten Telemetriedaten-Element.</param>
        <summary>
            Ein Element gesammelten Telemetriedaten zu verarbeiten.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>