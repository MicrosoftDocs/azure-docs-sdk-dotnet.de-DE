<Type Name="EntityHealth" FullName="System.Fabric.Health.EntityHealth">
  <TypeSignature Language="C#" Value="public abstract class EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit EntityHealth extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class EntityHealth" />
  <TypeSignature Language="F#" Value="type EntityHealth = class" />
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
      <para>Stellt die Basisklasse für alle Entitätsintegrität verknüpften Klassen.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected EntityHealth ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.EntityHealth.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.EntityHealth" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AggregatedHealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState AggregatedHealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState AggregatedHealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.EntityHealth.AggregatedHealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AggregatedHealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.AggregatedHealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.EntityHealth.AggregatedHealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Zustand der Entität, die aggregiert.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Fabric.Health.HealthState" /> Ereignisse auf die Entität und seine untergeordneten Elemente gemeldet, (sofern vorhanden) und des gewünschten Integritätsrichtlinie, die der aggregierte Integritätszustand berechnet vom Health Manager basierend auf darstellt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthEvents">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvent&gt; HealthEvents { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvent&gt; HealthEvents" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.EntityHealth.HealthEvents" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthEvents As IList(Of HealthEvent)" />
      <MemberSignature Language="F#" Value="member this.HealthEvents : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvent&gt;" Usage="System.Fabric.Health.EntityHealth.HealthEvents" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvent&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die integritätsereignisse für die Entität gemeldet.</para>
        </summary>
        <value>
          <para>Die integritätsereignisse bei der Entität gemeldet wird.</para>
        </value>
        <remarks>Die integritätsereignisse werden basierend auf Integritätsberichte gesendet in Health Store erstellt. Diese enthalten zusätzliche Metadaten, die vom Health Store hinzugefügt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.EntityHealth.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.EntityHealth.UnhealthyEvaluations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die fehlerhaften auswertungen, die zeigen, warum der aktuellen aggregierte Integritätsstatus vom Integritätsdienst zurückgegeben wurde.</para>
        </summary>
        <value>
          <para>Die fehlerhaften auswertungen, die beschreiben, warum der aktuellen aggregierte Integritätsstatus vom Integritätsdienst zurückgegeben wurde.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>