<Type Name="RepairTask" FullName="System.Fabric.Repair.RepairTask">
  <TypeSignature Language="C#" Value="public class RepairTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RepairTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.RepairTask" />
  <TypeSignature Language="VB.NET" Value="Public Class RepairTask" />
  <TypeSignature Language="F#" Value="type RepairTask = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt eine Aufgabe, reparieren, die erläutert, welche Art von Repair angefordert wurde, was ihren Status ist und was das endgültige Ergebnis war.</para>
      <para>Diese Klasse unterstützt die Service Fabric-Plattform. Es ist nicht vorgesehen, direkt aus Ihrem Code aufgerufen werden.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public string Action { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Action" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.Action" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Action As String" />
      <MemberSignature Language="F#" Value="member this.Action : string" Usage="System.Fabric.Repair.RepairTask.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den angeforderten Reparaturversuch ab.</para>
        </summary>
        <value>
          <para>Der angeforderte Reparaturversuch.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApprovedTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ApprovedTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ApprovedTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.ApprovedTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApprovedTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ApprovedTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.ApprovedTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Zeitpunkt, wenn die reparaturaufgabe Status "genehmigt" eingegeben.</para>
        </summary>
        <value>
          <para>Die Zeit, wenn die reparaturaufgabe Status "genehmigt" eingegeben.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClaimedTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ClaimedTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ClaimedTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.ClaimedTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClaimedTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ClaimedTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.ClaimedTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Zeitpunkt, wenn die reparaturaufgabe den Claimed-Status angenommen hat.</para>
        </summary>
        <value>
          <para>Die Zeit, wenn die reparaturaufgabe den Claimed-Status angenommen hat.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompletedTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CompletedTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CompletedTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.CompletedTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CompletedTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CompletedTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.CompletedTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Zeitpunkt, wenn die reparaturaufgabe den Status "Completed" eingegeben.</para>
        </summary>
        <value>
          <para>Die Zeit, wenn die reparaturaufgabe den Status "Completed" eingegeben.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.CreatedTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.CreatedTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Zeitpunkt, wenn die reparaturaufgabe Created-Zustand eingegeben.</para>
        </summary>
        <value>
          <para>Die Zeit, wenn die reparaturaufgabe Created-Zustand eingegeben.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="System.Fabric.Repair.RepairTask.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt eine Beschreibung des Zwecks oder andere nur zu Informationszwecken Details des Tasks "Reparieren".</para>
        </summary>
        <value>
          <para>Eine Beschreibung der Zweck und andere informative Details des Tasks "Reparieren".</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutingTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExecutingTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExecutingTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.ExecutingTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExecutingTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExecutingTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.ExecutingTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Zeitpunkt, wenn die reparaturaufgabe ausgeführten Zustand eingegeben.</para>
        </summary>
        <value>
          <para>Die Zeit, wenn die reparaturaufgabe ausgeführten Zustand eingegeben.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Executor">
      <MemberSignature Language="C#" Value="public string Executor { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Executor" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.Executor" />
      <MemberSignature Language="VB.NET" Value="Public Property Executor As String" />
      <MemberSignature Language="F#" Value="member this.Executor : string with get, set" Usage="System.Fabric.Repair.RepairTask.Executor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt den Namen der Executor für die Reparatur.</para>
        </summary>
        <value>
          <para>Der Name der Executor für die Reparatur.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutorData">
      <MemberSignature Language="C#" Value="public string ExecutorData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExecutorData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.ExecutorData" />
      <MemberSignature Language="VB.NET" Value="Public Property ExecutorData As String" />
      <MemberSignature Language="F#" Value="member this.ExecutorData : string with get, set" Usage="System.Fabric.Repair.RepairTask.ExecutorData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt eine Zeichenfolge, die der Executor für die Reparatur verwenden können, um den internen Zustand zu speichern.</para>
        </summary>
        <value>
          <para>Eine Datenzeichenfolge, die der Executor für die Reparatur verwenden können, um den internen Zustand zu speichern.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flags">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.RepairTaskFlags Flags { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Repair.RepairTaskFlags Flags" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.Flags" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Flags As RepairTaskFlags" />
      <MemberSignature Language="F#" Value="member this.Flags : System.Fabric.Repair.RepairTaskFlags" Usage="System.Fabric.Repair.RepairTask.Flags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Flags ab, mit die erhalten weitere Informationen über den Status des Tasks "Reparieren".</para>
        </summary>
        <value>
          <para>Die Flags, die zusätzliche Details über den Status des Tasks "Reparieren" enthalten.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Impact">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.RepairImpactDescription Impact { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Repair.RepairImpactDescription Impact" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.Impact" />
      <MemberSignature Language="VB.NET" Value="Public Property Impact As RepairImpactDescription" />
      <MemberSignature Language="F#" Value="member this.Impact : System.Fabric.Repair.RepairImpactDescription with get, set" Usage="System.Fabric.Repair.RepairTask.Impact" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairImpactDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ein Objekt, das die Auswirkungen der Reparatur beschreibt.</para>
        </summary>
        <value>
          <para>Ein <see cref="T:System.Fabric.Repair.RepairImpactDescription" /> Objekt, das die Auswirkungen der Reparatur beschreibt.</para>
        </value>
        <remarks>
          <para>Auswirkung muss angegeben werden, von der Executor für die Reparatur beim Übergang in den Zustand vorbereiten. Die auswirkungsobjekts bestimmt, welche Aktionen, die das System zur Vorbereitung der Auswirkungen der Reparatur, vor der Ausführung der Reparatur genehmigen dauert.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PerformPreparingHealthCheck">
      <MemberSignature Language="C#" Value="public bool PerformPreparingHealthCheck { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool PerformPreparingHealthCheck" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.PerformPreparingHealthCheck" />
      <MemberSignature Language="VB.NET" Value="Public Property PerformPreparingHealthCheck As Boolean" />
      <MemberSignature Language="F#" Value="member this.PerformPreparingHealthCheck : bool with get, set" Usage="System.Fabric.Repair.RepairTask.PerformPreparingHealthCheck" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt einen Wert zu ermitteln, ob integritätsprüfungen ausgeführt werden, wenn die reparaturaufgabe vorbereiten wechselt.</para>
        </summary>
        <value>
          <para>Ein Wert, um festzustellen, ob integritätsprüfungen müssen ausgeführt werden, wenn die reparaturaufgabe vorbereiten wechselt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PerformRestoringHealthCheck">
      <MemberSignature Language="C#" Value="public bool PerformRestoringHealthCheck { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool PerformRestoringHealthCheck" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.PerformRestoringHealthCheck" />
      <MemberSignature Language="VB.NET" Value="Public Property PerformRestoringHealthCheck As Boolean" />
      <MemberSignature Language="F#" Value="member this.PerformRestoringHealthCheck : bool with get, set" Usage="System.Fabric.Repair.RepairTask.PerformRestoringHealthCheck" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt einen Wert zu bestimmen, ob Systemdiagnosen müssen ausgeführt werden, wenn die reparaturaufgabe Wiederherstellungsstatus eingibt.</para>
        </summary>
        <value>
          <para>Ein Wert, um festzustellen, ob integritätsprüfungen müssen ausgeführt werden, wenn die reparaturaufgabe Wiederherstellungsstatus eingibt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreparingHealthCheckEndTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreparingHealthCheckEndTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreparingHealthCheckEndTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.PreparingHealthCheckEndTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreparingHealthCheckEndTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreparingHealthCheckEndTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.PreparingHealthCheckEndTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Zeit, wenn die reparaturaufgabe den Zustand abgeschlossen, überprüfen im Status "Vorbereitung".</para>
        </summary>
        <value>
          <para>Überprüfen Sie die Zeit, wenn die reparaturaufgabe den Zustand abgeschlossen, im Status "Vorbereitung".</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreparingHealthCheckStartTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreparingHealthCheckStartTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreparingHealthCheckStartTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.PreparingHealthCheckStartTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreparingHealthCheckStartTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreparingHealthCheckStartTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.PreparingHealthCheckStartTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Startzeit der reparaturaufgabe die Integrität im Status "Vorbereitung" überprüfen.</para>
        </summary>
        <value>
          <para>Überprüfen Sie die Startzeit der reparaturaufgabe die Integrität im Status "Vorbereitung".</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreparingHealthCheckState">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.RepairTaskHealthCheckState PreparingHealthCheckState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Repair.RepairTaskHealthCheckState PreparingHealthCheckState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.PreparingHealthCheckState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreparingHealthCheckState As RepairTaskHealthCheckState" />
      <MemberSignature Language="F#" Value="member this.PreparingHealthCheckState : System.Fabric.Repair.RepairTaskHealthCheckState" Usage="System.Fabric.Repair.RepairTask.PreparingHealthCheckState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskHealthCheckState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Workflowstatus Systemdiagnose ab, wenn die reparaturaufgabe im Status "Vorbereitung" ist.</para>
        </summary>
        <value>
          <para>Die Workflowstatus Systemdiagnose, wenn die reparaturaufgabe im Status "Vorbereitung" ist.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreparingTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreparingTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreparingTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.PreparingTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreparingTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreparingTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.PreparingTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Zeitpunkt, wenn die reparaturaufgabe den Preparing-Status angenommen hat.</para>
        </summary>
        <value>
          <para>Die Zeit, wenn die reparaturaufgabe den Preparing-Status angenommen hat.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoringHealthCheckEndTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RestoringHealthCheckEndTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RestoringHealthCheckEndTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.RestoringHealthCheckEndTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RestoringHealthCheckEndTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RestoringHealthCheckEndTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.RestoringHealthCheckEndTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Zeit, wenn die reparaturaufgabe den Zustand abgeschlossen, checken Sie den Status Restoring.</para>
        </summary>
        <value>
          <para>Überprüfen Sie die Zeit, wenn die reparaturaufgabe den Zustand abgeschlossen, im Status Restoring.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoringHealthCheckStartTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RestoringHealthCheckStartTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RestoringHealthCheckStartTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.RestoringHealthCheckStartTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RestoringHealthCheckStartTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RestoringHealthCheckStartTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.RestoringHealthCheckStartTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Startzeit der reparaturaufgabe die Integrität im Restoring-Status überprüfen.</para>
        </summary>
        <value>
          <para>Die Startzeit der reparaturaufgabe die Integrität im Restoring-Status überprüfen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoringHealthCheckState">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.RepairTaskHealthCheckState RestoringHealthCheckState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Repair.RepairTaskHealthCheckState RestoringHealthCheckState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.RestoringHealthCheckState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RestoringHealthCheckState As RepairTaskHealthCheckState" />
      <MemberSignature Language="F#" Value="member this.RestoringHealthCheckState : System.Fabric.Repair.RepairTaskHealthCheckState" Usage="System.Fabric.Repair.RepairTask.RestoringHealthCheckState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskHealthCheckState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Workflowstatus Systemdiagnose ab, wenn die reparaturaufgabe im Wiederherstellungsstatus befindet.</para>
        </summary>
        <value>
          <para>Die Workflowstatus Systemdiagnose, wenn die reparaturaufgabe im Wiederherstellungsstatus befindet.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoringTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RestoringTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RestoringTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.RestoringTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RestoringTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RestoringTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.RestoringTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Zeitpunkt, wenn die reparaturaufgabe Wiederherstellungsstatus eingegeben.</para>
        </summary>
        <value>
          <para>Die Zeit, wenn die reparaturaufgabe Wiederherstellungsstatus eingegeben.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResultCode">
      <MemberSignature Language="C#" Value="public int ResultCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ResultCode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.ResultCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ResultCode As Integer" />
      <MemberSignature Language="F#" Value="member this.ResultCode : int with get, set" Usage="System.Fabric.Repair.RepairTask.ResultCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt einen Wert, der zusätzliche Informationen über das Ergebnis der Taskausführung reparieren.</para>
        </summary>
        <value>
          <para>Ein Wert, der zusätzliche Informationen über das Ergebnis der Taskausführung reparieren.</para>
        </value>
        <remarks>
          <para>Dieser Wert sollte ein HRESULT.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResultDetails">
      <MemberSignature Language="C#" Value="public string ResultDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResultDetails" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.ResultDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property ResultDetails As String" />
      <MemberSignature Language="F#" Value="member this.ResultDetails : string with get, set" Usage="System.Fabric.Repair.RepairTask.ResultDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt eine Zeichenfolge, die zusätzliche Informationen über das Ergebnis der Taskausführung reparieren.</para>
        </summary>
        <value>
          <para>Eine Zeichenfolge, die zusätzliche Informationen über das Ergebnis der Taskausführung reparieren.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResultStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.RepairTaskResult ResultStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Repair.RepairTaskResult ResultStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.ResultStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ResultStatus As RepairTaskResult" />
      <MemberSignature Language="F#" Value="member this.ResultStatus : System.Fabric.Repair.RepairTaskResult with get, set" Usage="System.Fabric.Repair.RepairTask.ResultStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt einen Wert, beschreibt das Gesamtergebnis der Taskausführung reparieren.</para>
        </summary>
        <value>
          <para>Ein <see cref="T:System.Fabric.Repair.RepairTaskResult" /> Wert, der das Gesamtergebnis der Taskausführung Reparatur beschreibt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.RepairScopeIdentifier Scope { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Repair.RepairScopeIdentifier Scope" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.Scope" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Scope As RepairScopeIdentifier" />
      <MemberSignature Language="F#" Value="member this.Scope : System.Fabric.Repair.RepairScopeIdentifier" Usage="System.Fabric.Repair.RepairTask.Scope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairScopeIdentifier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ein Objekt beschreibt den Bereich des Tasks "Reparieren".</para>
        </summary>
        <value>
          <para>Ein <see cref="T:System.Fabric.Repair.RepairScopeIdentifier" /> -Objekt, das den Bereich des Tasks "Reparieren" beschreibt.</para>
        </value>
        <remarks>
          <para>Die Reparatur Aufgabe Bereich ist festgelegt, die Ressource, mit die Hilfe Überprüfungen ausgeführt werden, wenn die reparaturaufgabe erstellt, geändert, gelöscht oder abgerufen wird.  Entitäten, die durch eine Reparatur betroffene müssen innerhalb des Bereichs des Tasks "Reparieren" enthalten sein.  Beispielsweise erfordern Reparaturen diese Auswirkungen auf die Knoten an, dass die reparaturaufgabe unter dem Bereich der Cluster erstellt werden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.RepairTaskState State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Repair.RepairTaskState State" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As RepairTaskState" />
      <MemberSignature Language="F#" Value="member this.State : System.Fabric.Repair.RepairTaskState with get, set" Usage="System.Fabric.Repair.RepairTask.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Abrufen oder Festlegen der Workflowstatus des Tasks "Reparieren".</para>
        </summary>
        <value>
          <para>Der Workflowstatus des Tasks "Reparieren".</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.RepairTargetDescription Target { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Repair.RepairTargetDescription Target" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.Target" />
      <MemberSignature Language="VB.NET" Value="Public Property Target As RepairTargetDescription" />
      <MemberSignature Language="F#" Value="member this.Target : System.Fabric.Repair.RepairTargetDescription with get, set" Usage="System.Fabric.Repair.RepairTask.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTargetDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt ein Objekt, beschreibt die Entitäten, die der angeforderten Reparaturversuch abzielt.</para>
        </summary>
        <value>
          <para>Ein Objekt, welche Entitäten beschreibt der angeforderten Reparaturversuch überprüft.</para>
        </value>
        <remarks>
          <para>Ziel ist möglicherweise null, wenn die Aktion zum Reparieren keine Informationen über bestimmte Ziele erforderlich ist.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskId">
      <MemberSignature Language="C#" Value="public string TaskId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.TaskId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskId As String" />
      <MemberSignature Language="F#" Value="member this.TaskId : string" Usage="System.Fabric.Repair.RepairTask.TaskId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Bezeichner des Tasks "Reparieren".</para>
        </summary>
        <value>
          <para>Der Bezeichner des Tasks "Reparieren".</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public long Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Version" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As Long" />
      <MemberSignature Language="F#" Value="member this.Version : int64 with get, set" Usage="System.Fabric.Repair.RepairTask.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die Version des Tasks "Reparieren".</para>
        </summary>
        <value>
          <para>Die Version des Tasks "Reparieren".</para>
        </value>
        <remarks>
          <para>Wenn Sie einen neuen Reparaturtask zu erstellen, muss die Version auf 0 (null) festgelegt werden.  Beim Aktualisieren von reparaturaufträgen über die UpdateRepairExecutionStateAsync-Methode wird die Version für Überprüfungen auf vollständige Parallelität verwendet.  Wenn die Version auf NULL gesetzt wird, wird das Update nicht für Write-Konflikte überprüfen.  Wenn die Version auf einen Wert ungleich 0 (null) festgelegt ist, wird das Update nur erfolgreich, wenn die tatsächliche aktuelle Version des Tasks "Reparieren" mit diesem Wert übereinstimmt.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>