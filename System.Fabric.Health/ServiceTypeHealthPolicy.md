<Type Name="ServiceTypeHealthPolicy" FullName="System.Fabric.Health.ServiceTypeHealthPolicy">
  <TypeSignature Language="C#" Value="public class ServiceTypeHealthPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceTypeHealthPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceTypeHealthPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceTypeHealthPolicy" />
  <TypeSignature Language="F#" Value="type ServiceTypeHealthPolicy = class" />
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
      <para>Stellt die Integritätsrichtlinie, die zur Bewertung der Integritäts von Diensten, die zu einem Diensttyp gehören.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceTypeHealthPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceTypeHealthPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.ServiceTypeHealthPolicy" />-Klasse.</para>
        </summary>
        <remarks>Standardmäßig werden keine Fehler oder Warnungen toleriert werden.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyPartitionsPerService">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyPartitionsPerService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyPartitionsPerService" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyPartitionsPerService" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyPartitionsPerService As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyPartitionsPerService : byte with get, set" Usage="System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyPartitionsPerService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die maximal zulässigen Prozentsatz fehlerhafter Partitionen pro Dienst.</para>
        </summary>
        <value>
          <para>Gibt die maximal zulässige Prozentsatz fehlerhafter Partitionen pro Dienst zurück.
            Zulässige Werte sind <see cref="T:System.Byte" /> Werte von 0 bis 100.</para>
        </value>
        <remarks>
          <para>
            Der Prozentsatz stellt den zulässigen maximalen Prozentsatz der Partitionen, die fehlerhaft sein kann, bevor der Dienst bei Fehler betrachtet wird. Wenn der Prozentsatz wird berücksichtigt, aber mindestens ein "fehlerhaft" Partition vorhanden ist, wird die Integrität als Warnung ausgewertet.
            Dies wird berechnet durch Dividieren der Anzahl der fehlerhaften Partitionen über die Gesamtanzahl der Partitionen im Dienst.
            Rundet auf die Berechnung auf kleinen Anzahl von Partitionen einen Ausfall tolerieren kann. Standardprozentsatz : null.
            </para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>Der angegebene Wert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyReplicasPerPartition">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyReplicasPerPartition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyReplicasPerPartition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyReplicasPerPartition" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyReplicasPerPartition As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyReplicasPerPartition : byte with get, set" Usage="System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyReplicasPerPartition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die maximal zulässigen Prozentsatz fehlerhafter Replikate pro Partition.</para>
        </summary>
        <value>
          <para>Gibt die maximal zulässige Prozentsatz fehlerhafter Replikate pro Partition zurück.
            Zulässige Werte sind <see cref="T:System.Byte" /> Werte von 0 bis 100.</para>
        </value>
        <remarks>
          <para>
            Der Prozentsatz stellt den zulässigen maximalen Prozentsatz der Replikate, die fehlerhaft sein kann, bevor die Partition bei Fehler betrachtet wird. Wenn der Prozentsatz wird berücksichtigt, aber mindestens ein "fehlerhaft" Replikat vorhanden ist, wird die Integrität als Warnung ausgewertet.
            Dies wird durch Dividieren die Anzahl der fehlerhaften Replikate über die Anzahl von Replikaten in der Partition berechnet.
            Rundet auf die Berechnung auf kleinere Mengen von Replikaten ein Ausfall tolerieren kann. Standardprozentsatz : null.
            </para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>Der angegebene Wert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyServices">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyServices { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyServices" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyServices" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyServices As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyServices : byte with get, set" Usage="System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyServices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die maximal zulässigen Prozentsatz fehlerhafter Dienste.</para>
        </summary>
        <value>
          <para>Gibt die maximal zulässige Prozentsatz fehlerhafter Dienste zurück. Zulässige Werte sind <see cref="T:System.Byte" /> Werte von 0 bis 100.</para>
        </value>
        <remarks>
          <para>
            Der Prozentsatz stellt den zulässigen maximalen Prozentsatz von Diensten, die fehlerhaft sein kann, bevor die Anwendung bei Fehler betrachtet wird. Wenn der Prozentsatz wird berücksichtigt, aber mindestens ein "fehlerhaft" Dienst vorhanden ist, wird die Integrität als Warnung ausgewertet.
            Dies wird durch Division der "fehlerhaft" Dienste des Typs angegebenen Dienst über die Gesamtzahl der Dienste des Typs spezifischen Dienst berechnet.
            Rundet auf die Berechnung auf kleinere Mengen von Services ein Ausfall tolerieren kann. Standardprozentsatz : null.
            </para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>Der angegebene Wert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceTypeHealthPolicy.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceTypeHealthPolicy.ToString " />
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
            Ruft eine Zeichenfolgendarstellung der Integritätsrichtlinie für Service-Typ ab.
            </summary>
        <returns>Eine Zeichenfolgendarstellung der Integritätsrichtlinie für Service-Typ.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>