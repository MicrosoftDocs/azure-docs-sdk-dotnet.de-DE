<Type Name="ITelemetryInitializer" FullName="Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer">
  <TypeSignature Language="C#" Value="public interface ITelemetryInitializer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITelemetryInitializer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITelemetryInitializer" />
  <TypeSignature Language="F#" Value="type ITelemetryInitializer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Stellt ein Objekt, das initialisiert <see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" /> Objekte.
            </summary>
    <remarks>
            Die <see cref="T:Microsoft.ApplicationInsights.DataContracts.TelemetryContext" /> Instanzen verwenden <see cref="T:Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer" /> -Objekten, Eigenschaften von Automatisches Initialisieren der <see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" /> Objekte.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (Microsoft.ApplicationInsights.Channel.ITelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class Microsoft.ApplicationInsights.Channel.ITelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer.Initialize(Microsoft.ApplicationInsights.Channel.ITelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (telemetry As ITelemetry)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : Microsoft.ApplicationInsights.Channel.ITelemetry -&gt; unit" Usage="iTelemetryInitializer.Initialize telemetry" />
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
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.Channel.ITelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry">To be added.</param>
        <summary>
            Initialisiert die Eigenschaften des angegebenen <see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" /> Objekt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>