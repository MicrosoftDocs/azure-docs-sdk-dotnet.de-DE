<Type Name="HealthEvent" FullName="System.Fabric.Health.HealthEvent">
  <TypeSignature Language="C#" Value="public sealed class HealthEvent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HealthEvent extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthEvent" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HealthEvent" />
  <TypeSignature Language="F#" Value="type HealthEvent = class" />
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
      <para>Stellt Integritätsinformationen für eine Integrität-Entität, z. B. Cluster, Anwendung oder Knoten mit zusätzlichen Metadaten, die vom Health Manager hinzugefügt gemeldet.</para>
    </summary>
    <remarks>Integritätsereignisse werden von integritätsabfragen zurückgegeben, wie z. B. <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />.
            Sie enthalten <see cref="T:System.Fabric.Health.HealthInformation" /> gesendet, Clientintegritäts-Managers in einem <see cref="T:System.Fabric.Health.HealthReport" />.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthInformation">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthInformation HealthInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthInformation HealthInformation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.HealthInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthInformation As HealthInformation" />
      <MemberSignature Language="F#" Value="member this.HealthInformation : System.Fabric.Health.HealthInformation" Usage="System.Fabric.Health.HealthEvent.HealthInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Zustandsinformationen, die in Health Store in gesendet wurde eine <see cref="T:System.Fabric.Health.HealthReport" />.</para>
        </summary>
        <value>
          <para>Die Zustandsinformationen, die in Health Store in gesendet wurde eine <see cref="T:System.Fabric.Health.HealthReport" />.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsExpired">
      <MemberSignature Language="C#" Value="public bool IsExpired { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsExpired" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.IsExpired" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsExpired As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsExpired : bool" Usage="System.Fabric.Health.HealthEvent.IsExpired" />
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
          <para>Ruft einen Wert, der angibt, ob das integritätsereignis abgelaufen ist.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> ist das integritätsereignis abgelaufen; <languageKeyword>"false"</languageKeyword> , wenn das integritätsereignis nicht zur Zeit abgelaufen war ausgewertet, der Health Store die Abfrage.</para>
        </value>
        <remarks>
          <para>Ein Ereignis kann nur ablaufen, wenn RemoveWhenExpired auf „false“ festgelegt ist.
            Andernfalls wird das Ereignis von der Abfrage nicht zurückgegeben und aus dem Speicher entfernt.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastErrorTransitionAt">
      <MemberSignature Language="C#" Value="public DateTime LastErrorTransitionAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastErrorTransitionAt" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastErrorTransitionAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastErrorTransitionAt : DateTime" Usage="System.Fabric.Health.HealthEvent.LastErrorTransitionAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Wenn die aktuelle <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> ist <see cref="F:System.Fabric.Health.HealthState.Error" />, gibt der Zeitpunkt, an dem der Bericht zur Integrität ersten wurde, gemeldet, mit <see cref="F:System.Fabric.Health.HealthState.Error" />. Für die regelmäßige Berichterstattung viele Berichte mit demselben Status möglicherweise generiert wurden.</para>
          <para>Wenn die aktuelle <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> ist <see cref="F:System.Fabric.Health.HealthState.Ok" /> oder <see cref="F:System.Fabric.Health.HealthState.Warning" />, gibt die Zeit, an dem der Zustand des zuletzt im <see cref="F:System.Fabric.Health.HealthState.Error" />, bevor der Übergang in ein anderes. Wenn die <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> war noch nie <see cref="F:System.Fabric.Health.HealthState.Error" />, der Wert wird System.DateTime.FromFileTimeUtc(0) sein.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.DateTime" /> darstellt, die letzte Übergang Time (UTC) mit <see cref="F:System.Fabric.Health.HealthState.Error" />.</para>
        </value>
        <remarks>
          <para>Die Felder Übergang <see cref="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" /> Geben Sie den Verlauf der Integrität Zustandsübergänge für das Ereignis.
            Sie können auf intelligentere Warnungen oder Ereignisinformationen "Versionsgeschichte" Integrität verwendet werden. Sie ermöglichen Szenarien wie z. B.: <list type="bullet"> <item> <para>warnen, wenn eine Eigenschaft zur Warnung/Fehler für mehr als X Minuten wurde. Dies vermeidet Warnungen auf vorübergehende Bedingungen. Beispielsweise kann eine Warnung, wenn der Integritätsstatus für mehr als fünf Minuten Warnung wurde wurde übersetzt werden, in ("healthstate" Warnung "und" jetzt - LastWarningTransitionTime == &gt; 5 Minuten).</para> </item> <item> <para>Warnung nur bei Bedingungen, die in den letzten geändert haben X Minuten. Ein Bericht vor dem angegebenen Zeitpunkt bereits Fehlers war, kann ignoriert werden, da es bereits zuvor signalisiert wurde. </para> </item> <item> <para>, Wenn eine Eigenschaft, die zwischen den Warnungs- und umschalten ist, zu bestimmen, wie lange sie "fehlerhaft" (d. h. nicht OK) wurde. Beispielsweise kann eine Warnung, wenn die Eigenschaft nicht mehr als fünf Minuten fehlerfrei wurde in übersetzt werden ("healthstate"! = Ok und Now - LastOkTransitionTime &gt; 5 Minuten).</para></item></list></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedUtcTimestamp">
      <MemberSignature Language="C#" Value="public DateTime LastModifiedUtcTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastModifiedUtcTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.LastModifiedUtcTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedUtcTimestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastModifiedUtcTimestamp : DateTime" Usage="System.Fabric.Health.HealthEvent.LastModifiedUtcTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft das Datum und die Uhrzeit der letzten der Bericht zur Integrität von dem Health Store Änderung.</para>
        </summary>
        <value>
          <para>Das Datum und Uhrzeit der letzten der Bericht zur Integrität von dem Health Store Änderung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastOkTransitionAt">
      <MemberSignature Language="C#" Value="public DateTime LastOkTransitionAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastOkTransitionAt" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastOkTransitionAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastOkTransitionAt : DateTime" Usage="System.Fabric.Health.HealthEvent.LastOkTransitionAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Wenn die aktuelle <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> ist <see cref="F:System.Fabric.Health.HealthState.Ok" />, gibt der Zeitpunkt, an dem der Bericht zur Integrität ersten wurde, gemeldet, mit <see cref="F:System.Fabric.Health.HealthState.Ok" />. Für die regelmäßige Berichterstattung viele Berichte mit demselben Status möglicherweise generiert wurden.</para>
          <para>Wenn die aktuelle <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> ist <see cref="F:System.Fabric.Health.HealthState.Error" /> oder <see cref="F:System.Fabric.Health.HealthState.Warning" />, gibt die Zeit, an dem der Zustand des zuletzt im <see cref="F:System.Fabric.Health.HealthState.Ok" />, bevor der Übergang in ein anderes. Wenn die <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> war noch nie <see cref="F:System.Fabric.Health.HealthState.Ok" />, der Wert wird System.DateTime.FromFileTimeUtc(0) sein.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.DateTime" /> darstellt, die letzte Übergang Time (UTC) mit <see cref="F:System.Fabric.Health.HealthState.Ok" />.</para>
        </value>
        <remarks>
          <para>Die Felder Übergang <see cref="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" /> Geben Sie den Verlauf der Integrität Zustandsübergänge für das Ereignis.
            Sie können auf intelligentere Warnungen oder Ereignisinformationen "Versionsgeschichte" Integrität verwendet werden. Sie ermöglichen Szenarien wie z. B.: <list type="bullet"> <item> <para>warnen, wenn eine Eigenschaft zur Warnung/Fehler für mehr als X Minuten wurde. Dies vermeidet Warnungen auf vorübergehende Bedingungen. Beispielsweise kann eine Warnung, wenn der Integritätsstatus für mehr als fünf Minuten Warnung wurde wurde übersetzt werden, in ("healthstate" Warnung "und" jetzt - LastWarningTransitionTime == &gt; 5 Minuten).</para> </item> <item> <para>Warnung nur bei Bedingungen, die in den letzten geändert haben X Minuten. Ein Bericht vor dem angegebenen Zeitpunkt bereits Fehlers war, kann ignoriert werden, da es bereits zuvor signalisiert wurde. </para> </item> <item> <para>, Wenn eine Eigenschaft, die zwischen den Warnungs- und umschalten ist, zu bestimmen, wie lange sie "fehlerhaft" (d. h. nicht OK) wurde. Beispielsweise kann eine Warnung, wenn die Eigenschaft nicht mehr als fünf Minuten fehlerfrei wurde in übersetzt werden ("healthstate"! = Ok und Now - LastOkTransitionTime &gt; 5 Minuten).</para></item></list></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastWarningTransitionAt">
      <MemberSignature Language="C#" Value="public DateTime LastWarningTransitionAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastWarningTransitionAt" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastWarningTransitionAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastWarningTransitionAt : DateTime" Usage="System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Wenn die aktuelle <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> ist <see cref="F:System.Fabric.Health.HealthState.Warning" />, gibt der Zeitpunkt, an dem der Bericht zur Integrität ersten wurde, gemeldet, mit <see cref="F:System.Fabric.Health.HealthState.Warning" />. Für die regelmäßige Berichterstattung viele Berichte mit demselben Status möglicherweise generiert wurden.</para>
          <para>Wenn die aktuelle <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> ist <see cref="F:System.Fabric.Health.HealthState.Ok" /> oder <see cref="F:System.Fabric.Health.HealthState.Error" />, gibt die Zeit, an dem der Zustand des zuletzt im <see cref="F:System.Fabric.Health.HealthState.Warning" />, bevor der Übergang in ein anderes. Wenn die <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> war noch nie <see cref="F:System.Fabric.Health.HealthState.Warning" />, der Wert wird System.DateTime.FromFileTimeUtc(0) sein.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.DateTime" /> darstellt, die letzte Übergang Time (UTC) mit <see cref="F:System.Fabric.Health.HealthState.Warning" />.</para>
        </value>
        <remarks>
          <para>Die Felder Übergang <see cref="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" /> Geben Sie den Verlauf der Integrität Zustandsübergänge für das Ereignis.
            Sie können auf intelligentere Warnungen oder Ereignisinformationen "Versionsgeschichte" Integrität verwendet werden. Sie ermöglichen Szenarien wie z. B.: <list type="bullet"> <item> <para>warnen, wenn eine Eigenschaft zur Warnung/Fehler für mehr als X Minuten wurde. Dies vermeidet Warnungen auf vorübergehende Bedingungen. Beispielsweise kann eine Warnung, wenn der Integritätsstatus für mehr als fünf Minuten Warnung wurde wurde übersetzt werden, in ("healthstate" Warnung "und" jetzt - LastWarningTransitionTime == &gt; 5 Minuten).</para> </item> <item> <para>Warnung nur bei Bedingungen, die in den letzten geändert haben X Minuten. Ein Bericht vor dem angegebenen Zeitpunkt bereits Fehlers war, kann ignoriert werden, da es bereits zuvor signalisiert wurde. </para> </item> <item> <para>, Wenn eine Eigenschaft, die zwischen den Warnungs- und umschalten ist, zu bestimmen, wie lange sie "fehlerhaft" (d. h. nicht OK) wurde. Beispielsweise kann eine Warnung, wenn die Eigenschaft nicht mehr als fünf Minuten fehlerfrei wurde in übersetzt werden ("healthstate"! = Ok und Now - LastOkTransitionTime &gt; 5 Minuten).</para></item></list></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceUtcTimestamp">
      <MemberSignature Language="C#" Value="public DateTime SourceUtcTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime SourceUtcTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.SourceUtcTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceUtcTimestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.SourceUtcTimestamp : DateTime" Usage="System.Fabric.Health.HealthEvent.SourceUtcTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft das Datum und Uhrzeit, wann der Bericht zur Integrität von der Quelle gesendet wurde.</para>
        </summary>
        <value>
          <para>Datum und Uhrzeit, wann der Bericht zur Integrität von der Quelle gesendet wurde.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthEvent.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="healthEvent.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft eine Zeichenfolgendarstellung der integritätsereignis ab.
            </summary>
        <returns>Eine Zeichenfolgendarstellung der integritätsereignis.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>