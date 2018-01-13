<Type Name="ReplicaRole" FullName="System.Fabric.ReplicaRole">
  <TypeSignature Language="C#" Value="public enum ReplicaRole" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ReplicaRole extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ReplicaRole" />
  <TypeSignature Language="VB.NET" Value="Public Enum ReplicaRole" />
  <TypeSignature Language="F#" Value="type ReplicaRole = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Gibt die Rolle eines zustandsbehafteten dienstreplikats an. </para>
    </summary>
    <remarks>
      <para>Service Fabric ist aus einem Replikat Dienst abhängig von der derzeit ausgeführten Rolle unterschiedliche Verhaltensweisen erforderlich.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ActiveSecondary">
      <MemberSignature Language="C#" Value="ActiveSecondary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReplicaRole ActiveSecondary = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReplicaRole.ActiveSecondary" />
      <MemberSignature Language="VB.NET" Value="ActiveSecondary" />
      <MemberSignature Language="F#" Value="ActiveSecondary = 4" Usage="System.Fabric.ReplicaRole.ActiveSecondary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaRole</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>Bezieht sich auf ein Replikat in der Gruppe, die statusaktualisierungen vom primären Replikat empfängt, anwendet und Bestätigungen zurücksendet. Sekundäre Replikate müssen am schreibquorum für eine Replikatgruppe teilnehmen. Es können mehrere aktive sekundäre Replikate in einer Replikatgruppe zu einem Zeitpunkt vorhanden sein. Die Anzahl der aktiven sekundären Replikate ist konfigurierbar, dass es sich bei das für systemzuverlässigkeit eingesetzten Subsystem verwalten soll.  </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="IdleSecondary">
      <MemberSignature Language="C#" Value="IdleSecondary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReplicaRole IdleSecondary = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReplicaRole.IdleSecondary" />
      <MemberSignature Language="VB.NET" Value="IdleSecondary" />
      <MemberSignature Language="F#" Value="IdleSecondary = 3" Usage="System.Fabric.ReplicaRole.IdleSecondary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaRole</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>Bezieht sich auf ein Replikat in der Gruppe, die eine Übertragung Zustand vom primären Replikat zur Vorbereitung der immer als aktives sekundäres Replikat empfängt. Es können mehrere inaktive sekundäre Replikate in einer Replikatgruppe zu einem Zeitpunkt vorhanden sein. Inaktive sekundäre Replikate werden nicht als Teil eines schreibquorums gezählt. </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReplicaRole None = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReplicaRole.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 1" Usage="System.Fabric.ReplicaRole.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaRole</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass das Replikat keine Verantwortung hinsichtlich der Replikatgruppe aufweist.</para>
        </summary>
        <remarks>
          <para>Wenn <see cref="M:System.Fabric.IStatefulServiceReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" /> gibt dieser Rolle kann gefahrlos alle persistenten Status zu löschen, die dieses Replikat zugeordnet ist.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Primary">
      <MemberSignature Language="C#" Value="Primary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReplicaRole Primary = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReplicaRole.Primary" />
      <MemberSignature Language="VB.NET" Value="Primary" />
      <MemberSignature Language="F#" Value="Primary = 2" Usage="System.Fabric.ReplicaRole.Primary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaRole</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>Bezieht sich auf das Replikat in der, das Gruppe auf das alle Lese- und Schreibzugriff Operations um Semantik mit starker Konsistenz durchzusetzen abgeschlossen sind. Lesevorgänge werden direkt vom primären Replikat verarbeitet, während Schreibvorgänge durch ein Quorum der Replikate in der Replikatgruppe bestätigt werden müssen. Es kann nur ein primäres Replikat in einer Replikatgruppe zu einem Zeitpunkt vorhanden sein. </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Unknown">
      <MemberSignature Language="C#" Value="Unknown" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReplicaRole Unknown = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReplicaRole.Unknown" />
      <MemberSignature Language="VB.NET" Value="Unknown" />
      <MemberSignature Language="F#" Value="Unknown = 0" Usage="System.Fabric.ReplicaRole.Unknown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaRole</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Gibt die erste Rolle, der in ein Replikat erstellt wurde.</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>