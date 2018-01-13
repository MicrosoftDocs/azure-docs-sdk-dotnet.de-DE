<Type Name="ITelemetry" FullName="Microsoft.ApplicationInsights.Channel.ITelemetry">
  <TypeSignature Language="C#" Value="public interface ITelemetry" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITelemetry" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Channel.ITelemetry" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITelemetry" />
  <TypeSignature Language="F#" Value="type ITelemetry = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Der Basis Telemetrie-Typ für das Application Insights.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.ITelemetry.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As TelemetryContext" />
      <MemberSignature Language="F#" Value="member this.Context : Microsoft.ApplicationInsights.DataContracts.TelemetryContext" Usage="Microsoft.ApplicationInsights.Channel.ITelemetry.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.DataContracts.TelemetryContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Kontext dieser Telemetrie-Instanz zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeepClone">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Channel.ITelemetry.DeepClone" />
      <MemberSignature Language="VB.NET" Value="Public Function DeepClone () As ITelemetry" />
      <MemberSignature Language="F#" Value="abstract member DeepClone : unit -&gt; Microsoft.ApplicationInsights.Channel.ITelemetry" Usage="iTelemetry.DeepClone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Channel.ITelemetry</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sanitize">
      <MemberSignature Language="C#" Value="public void Sanitize ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Sanitize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize" />
      <MemberSignature Language="VB.NET" Value="Public Sub Sanitize ()" />
      <MemberSignature Language="F#" Value="abstract member Sanitize : unit -&gt; unit" Usage="iTelemetry.Sanitize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Bereinigt die Eigenschaften der Telemetrie-Elements, das basierend auf DP-Einschränkungen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sequence">
      <MemberSignature Language="C#" Value="public string Sequence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sequence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.ITelemetry.Sequence" />
      <MemberSignature Language="VB.NET" Value="Public Property Sequence As String" />
      <MemberSignature Language="F#" Value="member this.Sequence : string with get, set" Usage="Microsoft.ApplicationInsights.Channel.ITelemetry.Sequence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Wert an, der absolute Reihenfolge der Telemetrie-Elements definiert.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die Sequenz dient zum Nachverfolgen von absolute Reihenfolge der hochgeladenen Telemetrie-Elemente. Es ist ein mit dem zweiteiligen-Wert, der einen stabilen Bezeichner für die aktuelle Boot-Sitzung und ein inkrementeller Bezeichner für jedes Ereignis hinzugefügt wird, um der Upload-Warteschlange enthält: für UTC dies die für alle Ereignisse im System erhöhen würde.
            Für den permanenten Speicher würde dies für alle Ereignisse aus den Hostprozess ausgegeben erhöht.    
            Die Sequenz können verfolgen, wie viele Ereignisse ausgelöst wurden und wie viele Ereignisse hochgeladen wurden und aktiviert die Identifizierung von Daten während der Upload- und Deduplizierung der Ereignisse auf dem Server eingehend verloren gehen.
            Aus <a href="https://microsoft.sharepoint.com/teams/CommonSchema/Shared%20Documents/Schema%20Specs/Common%20Schema%202%20-%20Language%20Specification.docx" />.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.ITelemetry.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.ApplicationInsights.Channel.ITelemetry.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Datum und Uhrzeit, wann Telemetrie aufgezeichnet wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>