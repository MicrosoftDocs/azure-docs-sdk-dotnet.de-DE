<Type Name="ReplicatorSettings" FullName="System.Fabric.ReplicatorSettings">
  <TypeSignature Language="C#" Value="public sealed class ReplicatorSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicatorSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ReplicatorSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicatorSettings" />
  <TypeSignature Language="F#" Value="type ReplicatorSettings = class" />
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
      <para>Ermöglicht ein zustandsbehaftetes Replikat so konfigurieren Sie die <see cref="T:System.Fabric.FabricReplicator" /> auch über die Erstellung <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicatorSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ReplicatorSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.ReplicatorSettings" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchAcknowledgementInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; BatchAcknowledgementInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; BatchAcknowledgementInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchAcknowledgementInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.BatchAcknowledgementInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die Zeitspanne, die der Replikator nach dem Empfang eines Vorgangs vor dem Zurücksenden einer Bestätigung wartet. </para>
        </summary>
        <value>
          <para>Die Zeitspanne, die der Replikator nach dem Empfang eines Vorgangs vor dem Zurücksenden einer Bestätigung wartet.</para>
        </value>
        <remarks>
          <para>Andere Vorgänge empfangen und während dieses Zeitraums bestätigt haben ihre Bestätigungen wieder in einer einzelnen Nachricht gesendet.</para>
          <para>Erhöhen der <see cref="P:System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" /> Wert verringert die Latenz der einzelnen Replikationsvorgängen jedoch erhöht den Durchsatz der Replikator.</para>
          <para>Standardwert ist 0,05 Sekunden (50 Millisekunden)</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialCopyQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialCopyQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialCopyQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.InitialCopyQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialCopyQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialCopyQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.InitialCopyQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die Anfangsgröße der Kopie Vorgangswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, das Kopie enthält <see cref="T:System.Fabric.IOperation" />s noch nicht gepumpt und vom Dienst verarbeitet.</para>
        </summary>
        <value>
          <para>Die Anfangsgröße der Vorgangswarteschlange Kopie innerhalb <see cref="T:System.Fabric.FabricReplicator" />, das Kopie enthält <see cref="T:System.Fabric.IOperation" />s noch nicht gepumpt und vom Dienst verarbeitet.</para>
        </value>
        <remarks>
          <para>Der Standardwert ist 64. Beachten Sie, dass die Werte für diesen Parameter eine Potenz von 2 sein müssen.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialPrimaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialPrimaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialPrimaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.InitialPrimaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialPrimaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialPrimaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.InitialPrimaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Definiert die anfängliche Größe der primären Replikation Vorgangswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s.The Einheit hier ist die Anzahl der Vorgänge in der Warteschlange.</para>
        </summary>
        <value>
          <para>Die Anfangsgröße der primären Replikation Vorgangswarteschlange innerhalb<see cref="T:System.Fabric.FabricReplicator" /></para>
        </value>
        <remarks>
          <para>Diese Einstellung bezieht sich auf Replikator, wenn die Rolle des Diensts primären</para>
          <para>Der Standardwert ist 64.  Beachten Sie, dass die Werte für diesen Parameter eine Potenz von 2 sein müssen.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.InitialReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.InitialReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die Anfangsgröße der Größe der Replikation.</para>
        </summary>
        <value>
          <para>Die Anfangsgröße der Größe der Replikation.</para>
        </value>
        <remarks>
          <para />
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialSecondaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialSecondaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialSecondaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.InitialSecondaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialSecondaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialSecondaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.InitialSecondaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Definiert die anfängliche Größe des sekundären Vorgang Replikationswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s </para>
        </summary>
        <value>
          <para>Die Anfangsgröße der sekundären Vorgang Replikationswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s noch nicht gepumpt und vom Dienst verarbeitet. Die Einheit hier ist die Anzahl der Vorgänge in der Warteschlange </para>
        </value>
        <remarks>
          <para>Diese Einstellung bezieht sich auf Replikator, wenn die Rolle des Diensts Sekundär/Leerlauf</para>
          <para>Der Standardwert ist 64.  Beachten Sie, dass die Werte für diesen Parameter eine Potenz von 2 sein müssen.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFrom">
      <MemberSignature Language="C#" Value="public static System.Fabric.ReplicatorSettings LoadFrom (System.Fabric.CodePackageActivationContext codePackageActivationContext, string configPackageName, string sectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.ReplicatorSettings LoadFrom(class System.Fabric.CodePackageActivationContext codePackageActivationContext, string configPackageName, string sectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ReplicatorSettings.LoadFrom(System.Fabric.CodePackageActivationContext,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member LoadFrom : System.Fabric.CodePackageActivationContext * string * string -&gt; System.Fabric.ReplicatorSettings" Usage="System.Fabric.ReplicatorSettings.LoadFrom (codePackageActivationContext, configPackageName, sectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicatorSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codePackageActivationContext" Type="System.Fabric.CodePackageActivationContext" />
        <Parameter Name="configPackageName" Type="System.String" />
        <Parameter Name="sectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="codePackageActivationContext">
          <para>Die aktuelle Codepaket-Aktivierungskontext<see cref="T:System.Fabric.CodePackageActivationContext" /></para>
        </param>
        <param name="configPackageName">
          <para>Die aktuelle Konfiguration Paketname</para>
        </param>
        <param name="sectionName">
          <para>Im Abschnitt in der Konfigurationsdatei, die alle Replikator Einstellungen definiert.</para>
        </param>
        <summary>
          <para>Lädt die <see cref="T:System.Fabric.ReplicatorSettings" /> Objekt aus den Einstellungen der Dienstkonfigurationsdatei.</para>
        </summary>
        <returns>
          <para>Das geladene <see cref="T:System.Fabric.ReplicatorSettings" /> Objekt aus den Einstellungen der Dienstkonfigurationsdatei</para>
        </returns>
        <remarks>
          <para> Die Einstellungen Konfigurationsdatei ("Settings.xml") in den Konfigurationsordner Dienst in der Regel enthält die Replicator-Einstellungen, die erforderlich ist, übergeben die <see cref="T:System.Fabric.ReplicatorSettings" /> -Objekt an die <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" /> Methode. In der Regel bleibt auf den dienstautor, lesen Sie die Datei "Settings.xml", analysieren Sie die Werte aus, und erstellen entsprechend der <see cref="T:System.Fabric.ReplicatorSettings" /> Objekt.</para>
          <para>Mit der aktuellen Hilfsmethode kann den oben aufgeführten Vorgang dienstautor umgangen werden.</para>
          <para>Es folgen die Namen der Parameter, die in der Dienstkonfiguration "settings.xml" von Windows Fabric, um die oben genannten Analyse automatisch erkannt werden bereitgestellt werden sollten:</para>
          <list type="number">
            <item>
              <description>
                <para>BatchAcknowledgementInterval –<see cref="P:System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" /> Wert in Sekunden</para>
              </description>
            </item>
            <item>
              <description>
                <para>InitialCopyQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.InitialCopyQueueSize" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>MaxCopyQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.MaxCopyQueueSize" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>MaxReplicationMessageSize-<see cref="P:System.Fabric.ReplicatorSettings.MaxReplicationMessageSize" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>RetryInterval -<see cref="P:System.Fabric.ReplicatorSettings.RetryInterval" /> Wert in Sekunden</para>
              </description>
            </item>
            <item>
              <description>
                <para>RequireServiceAck-<see cref="P:System.Fabric.ReplicatorSettings.RequireServiceAck" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>ReplicatorAddress oder ReplicatorEndpoint – sollten ReplicatorAddress des Formulars IPort sein. ReplicatorEndpoint muss eine gültigen Endpunkt Dienstressource von im Dienstmanifest verweisen-<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorAddress" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>ReplicatorListenAddress oder ReplicatorEndpoint – sollten ReplicatorListenAddress des Formulars IPort sein. ReplicatorEndpoint muss eine gültigen Endpunkt Dienstressource von im Dienstmanifest verweisen-<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorListenAddress" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>ReplicatorPublishAddress oder ReplicatorEndpoint – sollten ReplicatorPublishAddress des Formulars IPort sein. ReplicatorEndpoint muss eine gültigen Endpunkt Dienstressource von im Dienstmanifest verweisen-<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>SecondaryClearAcknowledgedOperations-<see cref="P:System.Fabric.ReplicatorSettings.SecondaryClearAcknowledgedOperations" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>PrimaryWaitForPendingQuorumsTimeout - <see cref="P:System.Fabric.ReplicatorSettings.PrimaryWaitForPendingQuorumsTimeout" /> Wert in Sekunden</para>
              </description>
            </item>
            <item>
              <description>
                <para>UseStreamFaultsAndEndOfStreamOperationAck-<see cref="P:System.Fabric.ReplicatorSettings.UseStreamFaultsAndEndOfStreamOperationAck" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>InitialPrimaryReplicationQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.InitialPrimaryReplicationQueueSize" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>InitialSecondaryReplicationQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.InitialSecondaryReplicationQueueSize" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>MaxPrimaryReplicationQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueSize" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>MaxSecondaryReplicationQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueSize" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>MaxPrimaryReplicationQueueMemorySize-<see cref="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueMemorySize" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>MaxSecondaryReplicationQueueMemorySize-<see cref="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueMemorySize" /></para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxCopyQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxCopyQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxCopyQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxCopyQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxCopyQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxCopyQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxCopyQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die maximale Größe der Warteschlange Vorgang Kopie innerhalb <see cref="T:System.Fabric.FabricReplicator" />, das Kopie enthält <see cref="T:System.Fabric.IOperation" />s noch nicht gepumpt und vom Dienst verarbeitet.</para>
        </summary>
        <value>
          <para>Die maximale Größe der Warteschlange Vorgang Kopie innerhalb <see cref="T:System.Fabric.FabricReplicator" />, das Kopie enthält <see cref="T:System.Fabric.IOperation" />s noch nicht gepumpt und vom Dienst verarbeitet.</para>
        </value>
        <remarks>
          <para>Wenn die Größe der Sendewarteschlange auf dem sekundären Server erreicht ist, werden Vorgänge in der primären Kopiewarteschlange gepuffert werden. Wenn diese Warteschlange auch voll ist, wird angezeigt, die primäre beginnt <see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" /> Ausnahmen.</para>
          <para>Der Standardwert ist 1024</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPrimaryReplicationQueueMemorySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxPrimaryReplicationQueueMemorySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxPrimaryReplicationQueueMemorySize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPrimaryReplicationQueueMemorySize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxPrimaryReplicationQueueMemorySize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueMemorySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Definiert die maximale Größe der primären Replikation Vorgangswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s</para>
        </summary>
        <value>
          <para>zu erstellen und zu verwalten. Gibt die maximale Größe der primären Replikation Vorgangswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s hier die Einheit ist der virtuelle Arbeitsspeicherverbrauch der Warteschlange. Gibt <see cref="T:System.Int64" />.</para>
        </value>
        <remarks>
          <para>Diese Einstellung bezieht sich auf Replikator, wenn die Rolle des Diensts primär ist. Der Standardwert ist 0. Dies bedeutet, dass kein Arbeitsspeicherlimit vorhanden ist</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPrimaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxPrimaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxPrimaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPrimaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxPrimaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Definiert die maximale Größe der primären Replikation Vorgangswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s</para>
        </summary>
        <value>
          <para>Die maximale Größe der primären Replikation Vorgangswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s. Die Einheit hier ist die Anzahl der Vorgänge in der Warteschlange.</para>
        </value>
        <remarks>
          <para>Wenn diese Warteschlangengröße erreicht ist, wird angezeigt, die primäre beginnt <see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" /> Ausnahmen.</para>
          <para>Der Standardwert ist 1024 Hinweis, der Werte für diesen Parameter muss eine Potenz von 2 sein.</para>
          <para>Diese Einstellung bezieht sich auf Replikator, wenn die Rolle des Diensts primären</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReplicationMessageSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxReplicationMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxReplicationMessageSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxReplicationMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReplicationMessageSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxReplicationMessageSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxReplicationMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die maximale Größe einer Nachricht, die über die Replicator übertragen werden können. Diese Nachrichten enthalten, kopieren Sie Nachrichten und Kontext Meldungen kopieren. Die Einheit der Darstellung ist Bytes.</para>
        </summary>
        <value>
          <para>Die maximale Größe einer Nachricht, die über die Replicator übertragen werden können.</para>
        </value>
        <remarks>
          <para>Der Standardwert ist 50MB</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReplicationQueueMemorySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxReplicationQueueMemorySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxReplicationQueueMemorySize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxReplicationQueueMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReplicationQueueMemorySize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxReplicationQueueMemorySize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxReplicationQueueMemorySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die maximale Größe für die Replikation Warteschlange Arbeitsspeicher.</para>
        </summary>
        <value>
          <para>Die maximale Größe für die Replikation Warteschlange Arbeitsspeicher.</para>
        </value>
        <remarks>
          <para>Der Standardwert ist 0. Dies bedeutet, dass kein Arbeitsspeicherlimit vorhanden ist</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die maximale Größe für die Replikationswarteschlange.</para>
        </summary>
        <value>
          <para>die maximale Größe für die Replikationswarteschlange.</para>
        </value>
        <remarks>
          <para />
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSecondaryReplicationQueueMemorySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxSecondaryReplicationQueueMemorySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxSecondaryReplicationQueueMemorySize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSecondaryReplicationQueueMemorySize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxSecondaryReplicationQueueMemorySize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueMemorySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Definiert die maximale Größe des sekundären Vorgang Replikationswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s.</para>
        </summary>
        <value>
          <para>Gibt die maximale Größe des sekundären Vorgang Replikationswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s. Die Einheit hier ist der virtuelle Arbeitsspeicherverbrauch der Warteschlange.</para>
        </value>
        <remarks>
          <para>Diese Einstellung bezieht sich auf Replikator, wenn die Rolle des Diensts Sekundär/im Leerlauf ist. Der Standardwert ist 0. Dies bedeutet, dass kein Arbeitsspeicherlimit vorhanden ist</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSecondaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxSecondaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxSecondaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSecondaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxSecondaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Definiert die maximale Größe des sekundären Vorgang Replikationswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s </para>
        </summary>
        <value>
          <para>Die maximale Größe des sekundären Vorgang Replikationswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s noch nicht gepumpt und vom Dienst verarbeitet. Die Einheit hier ist die Anzahl der Vorgänge in der Warteschlange</para>
        </value>
        <remarks>
          <para>Wenn diese Größe erreicht ist, werden Vorgänge in der primären Replikationswarteschlange gepuffert werden.  Wenn diese Warteschlange auch voll ist, wird angezeigt, die primäre beginnt <see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" /> Ausnahmen.</para>
          <para>Der Standardwert ist 2048.Note, die Werte für diesen Parameter muss eine Potenz von 2 sein.</para>
          <para>Diese Einstellung bezieht sich auf Replikator, wenn die Rolle des Diensts Sekundär/Leerlauf</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryWaitForPendingQuorumsTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; PrimaryWaitForPendingQuorumsTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; PrimaryWaitForPendingQuorumsTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.PrimaryWaitForPendingQuorumsTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryWaitForPendingQuorumsTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.PrimaryWaitForPendingQuorumsTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.PrimaryWaitForPendingQuorumsTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Definiert, wie lange der primäre Replikator wartet, für den Empfang von einem Quorum von Bestätigungen für alle ausstehenden Replikationsvorgänge vor der Verarbeitung einer Neukonfiguration-Anforderung, die potenziell führen die ausstehenden Replikationsvorgänge dazu "Abbrechen".</para>
        </summary>
        <value>
          <para>Wartet, bis der primäre Replikator ein Quorum von Bestätigungen für alle ausstehenden Replikationsvorgängen empfangen, wenn es eine Anforderung für den primären Replikator zum Verarbeiten einer Neukonfiguration liegt Zeitspanne <see cref="T:System.TimeSpan" />.</para>
        </value>
        <remarks>
          <para>Der Standardwert ist 0. Dies bedeutet, dass für den Empfang von Quorum auf die ausstehende Replikationsvorgänge die Neukonfigurationen nach gewartet werden nicht. Dies hilft beim Abschließen der Neukonfigurationen früher. Beachten Sie, dass größere Werte für diesen Parameter möglicherweise langsamer Neukonfigurationen, Gleichzeichen längere dauern, um einen primären Failover führen können. </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorAddress">
      <MemberSignature Language="C#" Value="public string ReplicatorAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.ReplicatorAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicatorAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorAddress : string with get, set" Usage="System.Fabric.ReplicatorSettings.ReplicatorAddress" />
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
          <para>Konfiguriert die Adresse, die bei der Kommunikation mit anderen Replikatoren dieser Replikator verwenden.</para>
        </summary>
        <value>
          <para>Die Adresse, die bei der Kommunikation mit anderen Replikatoren dieser Replikator verwenden.</para>
        </value>
        <remarks>
          <para>Zeichenfolge wird als "Hostname:port", formatiert, in dem der Hostname FQDN oder IP-Adresse sein kann. Der Standardwert ist Localhost:0. Wenn Replikator innerhalb eines Containers ausgeführt wird, sollten Sie versuchen, das Einrichten <see cref="P:System.Fabric.ReplicatorSettings.ReplicatorListenAddress" /> und <see cref="P:System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorListenAddress">
      <MemberSignature Language="C#" Value="public string ReplicatorListenAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorListenAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.ReplicatorListenAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicatorListenAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorListenAddress : string with get, set" Usage="System.Fabric.ReplicatorSettings.ReplicatorListenAddress" />
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
          <para>Konfiguriert die abhöradresse, die diese Replikator zum Empfangen von Informationen aus anderen Replikatoren verwenden.</para>
        </summary>
        <value>
          <para>Die abhöradresse, die diese Replikator zum Empfangen von Informationen aus anderen Replikatoren verwenden.</para>
        </value>
        <remarks>
          <para>Zeichenfolge wird als "Hostname:port", formatiert, in dem der Hostname FQDN oder IP-Adresse sein kann. Der Standardwert ist Localhost:0. Hostname für abhöradresse kann aus abgerufen werden<see cref="P:System.Fabric.CodePackageActivationContext.ServiceListenAddress" /></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorPublishAddress">
      <MemberSignature Language="C#" Value="public string ReplicatorPublishAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorPublishAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicatorPublishAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorPublishAddress : string with get, set" Usage="System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" />
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
          <para>Konfiguriert die Publish-Adresse, die diese Replikator zum Senden von Informationen an andere Replikatoren verwenden.</para>
        </summary>
        <value>
          <para>Die Adresse der veröffentlichen, die diese Replikator zum Senden von Informationen an andere Replikatoren verwenden.</para>
        </value>
        <remarks>
          <para>Zeichenfolge wird als "Hostname:port", formatiert, in dem der Hostname FQDN oder IP-Adresse sein kann. Der Standardwert ist Localhost:0. Hostname für veröffentlichen Adresse kann von abgerufen werden<see cref="P:System.Fabric.CodePackageActivationContext.ServicePublishAddress" /></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequireServiceAck">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequireServiceAck { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequireServiceAck" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.RequireServiceAck" />
      <MemberSignature Language="VB.NET" Value="Public Property RequireServiceAck As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequireServiceAck : Nullable&lt;bool&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.RequireServiceAck" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Verhindert, dass die optimistische Bestätigung von Vorgängen in nicht persistente Dienste durch das anfordern, die der Dienst ruft <see cref="M:System.Fabric.IOperation.Acknowledge" /> , bevor er den nächsten Vorgang ruft.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn die vollständige Bestätigung von Vorgängen in nicht persistente Dienste; andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </value>
        <remarks>
          <para>Nicht persistenter Dienste, die explizite Bestätigung erfordern können diese Eigenschaft auf "true" festlegen, um zu verhindern, dass der Vorgänge vom Replikator optimistische Bestätigung. Diese Einstellung wirkt sich nicht bei beständigen Diensten aus. </para>
          <para>Der Standardwert ist „false“.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RetryInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RetryInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.RetryInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RetryInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.RetryInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Definiert, wie lange der <see cref="T:System.Fabric.FabricReplicator" /> wartet, nachdem er überträgt eine Nachricht vom primären auf die sekundäre Datenbank für die sekundäre Datenbank zu bestätigen, dass er die Nachricht empfangen hat.</para>
        </summary>
        <value>
          <para>Die benötigte Zeit die <see cref="T:System.Fabric.FabricReplicator" /> wartet, nachdem er überträgt eine Nachricht vom primären auf die sekundäre Datenbank für die sekundäre Datenbank zu bestätigen, dass er die Nachricht empfangen hat.</para>
        </value>
        <remarks>
          <para>Empfangen einer Nachricht wird nicht unbedingt, dass die Nachricht verarbeitet wurde.</para>
          <para>Wenn dieser Zeitgeber überschritten wird, wird die Nachricht erneut übertragen.</para>
          <para>Der Standardwert ist 5 Sekunden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryClearAcknowledgedOperations">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SecondaryClearAcknowledgedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SecondaryClearAcknowledgedOperations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.SecondaryClearAcknowledgedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryClearAcknowledgedOperations As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SecondaryClearAcknowledgedOperations : Nullable&lt;bool&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.SecondaryClearAcknowledgedOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Vorgänge in der sekundären Replikator bleiben in der Regel in der Warteschlange, Catchup Replikate Lage sein, wenn sie mit einem primären Replikat höher gestuft ist. Dieses Flag aktiviert ist gibt sekundären Replikator den Vorgang frei, sobald es vom Dienst für die bestätigt wird.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn sekundäre Replikator den Vorgang frei, sobald er durch den Dienst für die bestätigte ist, andernfalls ist <languageKeyword>"false"</languageKeyword>.</para>
        </value>
        <remarks>
          <para>Der Standardwert ist "false"</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityCredentials">
      <MemberSignature Language="C#" Value="public System.Fabric.SecurityCredentials SecurityCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SecurityCredentials SecurityCredentials" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.SecurityCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityCredentials As SecurityCredentials" />
      <MemberSignature Language="F#" Value="member this.SecurityCredentials : System.Fabric.SecurityCredentials with get, set" Usage="System.Fabric.ReplicatorSettings.SecurityCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SecurityCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ermöglicht dem Dienst um Sicherheitsanmeldeinformationen für die Sicherung des Datenverkehrs zwischen Replikatoren zu definieren.</para>
        </summary>
        <value>
          <para>Der Dienst zum Definieren der Sicherheitsanmeldeinformationen für die Sicherung des Datenverkehrs zwischen Replikatoren.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseStreamFaultsAndEndOfStreamOperationAck">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UseStreamFaultsAndEndOfStreamOperationAck { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UseStreamFaultsAndEndOfStreamOperationAck" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.UseStreamFaultsAndEndOfStreamOperationAck" />
      <MemberSignature Language="VB.NET" Value="Public Property UseStreamFaultsAndEndOfStreamOperationAck As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UseStreamFaultsAndEndOfStreamOperationAck : Nullable&lt;bool&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.UseStreamFaultsAndEndOfStreamOperationAck" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>