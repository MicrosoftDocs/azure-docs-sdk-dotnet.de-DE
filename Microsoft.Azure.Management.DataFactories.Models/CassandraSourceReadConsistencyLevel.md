<Type Name="CassandraSourceReadConsistencyLevel" FullName="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel">
  <TypeSignature Language="C#" Value="public static class CassandraSourceReadConsistencyLevel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CassandraSourceReadConsistencyLevel extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel" />
  <TypeSignature Language="VB.NET" Value="Public Class CassandraSourceReadConsistencyLevel" />
  <TypeSignature Language="F#" Value="type CassandraSourceReadConsistencyLevel = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Konsistenzebene der Cassandra-Datenbank herstellt.
            Eine Eigenschaft des <see cref="T:Microsoft.Azure.Management.DataFactories.Models.CassandraSource" />.
            Referenz: http://docs.datastax.com/en/cassandra/2.0/cassandra/dml/dml_config_consistency_c.html.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="All">
      <MemberSignature Language="C#" Value="public const string All;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string All" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.All" />
      <MemberSignature Language="VB.NET" Value="Public Const All As String " />
      <MemberSignature Language="F#" Value="val mutable All : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.All" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt den Datensatz zurück, nachdem alle Replikate geantwortet haben.
            Der Lesevorgang schlägt fehl, wenn ein Replikat nicht reagiert.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EachQuorum">
      <MemberSignature Language="C#" Value="public const string EachQuorum;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string EachQuorum" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.EachQuorum" />
      <MemberSignature Language="VB.NET" Value="Public Const EachQuorum As String " />
      <MemberSignature Language="F#" Value="val mutable EachQuorum : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.EachQuorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt den Datensatz zurück, sobald ein Quorum der Replikate in jedem Rechenzentrum des Clusters geantwortet hat.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalOne">
      <MemberSignature Language="C#" Value="public const string LocalOne;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string LocalOne" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.LocalOne" />
      <MemberSignature Language="VB.NET" Value="Public Const LocalOne As String " />
      <MemberSignature Language="F#" Value="val mutable LocalOne : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.LocalOne" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt eine Antwort vom nächstgelegenen Replikat im lokalen Rechenzentrum zurück.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalQuorum">
      <MemberSignature Language="C#" Value="public const string LocalQuorum;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string LocalQuorum" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.LocalQuorum" />
      <MemberSignature Language="VB.NET" Value="Public Const LocalQuorum As String " />
      <MemberSignature Language="F#" Value="val mutable LocalQuorum : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.LocalQuorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt zurück, den Datensatz nach dem ein Quorum der Replikate im aktuellen Rechenzentrum Koordinator gemeldet hat.
            Vermeidet die Latenz zwischen Data Center-Kommunikation.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalSerial">
      <MemberSignature Language="C#" Value="public const string LocalSerial;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string LocalSerial" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.LocalSerial" />
      <MemberSignature Language="VB.NET" Value="Public Const LocalSerial As String " />
      <MemberSignature Language="F#" Value="val mutable LocalSerial : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.LocalSerial" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Identisch mit der seriellen, aber im Rechenzentrum begrenzt. Ähnlich wie LOCAL_QUORUM.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="One">
      <MemberSignature Language="C#" Value="public const string One;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string One" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.One" />
      <MemberSignature Language="VB.NET" Value="Public Const One As String " />
      <MemberSignature Language="F#" Value="val mutable One : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.One" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt eine Antwort vom nächstgelegenen Replikat zurück, wie durch die Snitch bestimmt.
            Standardmäßig führt eine read-Reparatur im Hintergrund um den anderen Replikaten konsistent zu machen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Quorum">
      <MemberSignature Language="C#" Value="public const string Quorum;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Quorum" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.Quorum" />
      <MemberSignature Language="VB.NET" Value="Public Const Quorum As String " />
      <MemberSignature Language="F#" Value="val mutable Quorum : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.Quorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt den Datensatz zurück, nachdem ein Quorum der Replikate von jedem Rechenzentrum geantwortet hat.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serial">
      <MemberSignature Language="C#" Value="public const string Serial;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Serial" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.Serial" />
      <MemberSignature Language="VB.NET" Value="Public Const Serial As String " />
      <MemberSignature Language="F#" Value="val mutable Serial : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.Serial" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Lesen die aktuellen (und möglicherweise auch ohne Commit) Zustand der Daten ermöglicht ohne Syntaxfehlern neue hinzufügen oder Aktualisieren einer.
            Findet eine serielle Read uncommitted-Transaktion ausgeführt, führt es ein commit die Transaktion als Teil des Lesevorgangs. Zum Erzwingen eines QUORUMS vergleichbar. 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Three">
      <MemberSignature Language="C#" Value="public const string Three;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Three" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.Three" />
      <MemberSignature Language="VB.NET" Value="Public Const Three As String " />
      <MemberSignature Language="F#" Value="val mutable Three : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.Three" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt die neuesten Daten aus drei der nächstgelegene Replikate zurück.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Two">
      <MemberSignature Language="C#" Value="public const string Two;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Two" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.Two" />
      <MemberSignature Language="VB.NET" Value="Public Const Two As String " />
      <MemberSignature Language="F#" Value="val mutable Two : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.Two" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt die neuesten Daten aus zwei der nächstgelegene Replikate zurück.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>