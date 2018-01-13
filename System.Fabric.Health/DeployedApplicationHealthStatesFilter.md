<Type Name="DeployedApplicationHealthStatesFilter" FullName="System.Fabric.Health.DeployedApplicationHealthStatesFilter">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationHealthStatesFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationHealthStatesFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedApplicationHealthStatesFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationHealthStatesFilter" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealthStatesFilter = class" />
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
      <para>Stellt den Filter für <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> Objekte.</para>
    </summary>
    <remarks>Der Filter kann verwendet werden, <see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" /> an der bereitgestellten Anwendung untergeordnete Elemente zurückgegeben werden sollen, im Rahmen des <see cref="T:System.Fabric.Health.ApplicationHealth" />.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedApplicationHealthStatesFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealthStatesFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.DeployedApplicationHealthStatesFilter" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public long HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStatesFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As Long" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : int64 with get, set" Usage="System.Fabric.Health.DeployedApplicationHealthStatesFilter.HealthStateFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This property is obsolete. Use HealthStateFilterValue instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ALS VERALTET MARKIERT. Ruft ab oder legt ihn fest des Filters für den aggregierten Zustand der <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> Einträge in der Auflistung. Stellt einen Wert, der von Membern oder bitweisen Kombinationen von Elementen der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</para>
        </summary>
        <value>
          <para>Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> Einträge in der Auflistung.</para>
        </value>
        <remarks>Diese Eigenschaft ist veraltet. Verwenden Sie stattdessen <see cref="P:System.Fabric.Health.DeployedApplicationHealthStatesFilter.HealthStateFilterValue" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilterValue">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilterValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilterValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStatesFilter.HealthStateFilterValue" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilterValue As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilterValue : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.DeployedApplicationHealthStatesFilter.HealthStateFilterValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStateFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest des Filters für den aggregierten Zustand der <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> Einträge in der Auflistung. 
            </summary>
        <value>Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> Einträge.</value>
        <remarks>Die Eingabesammlung wird gefiltert, dass nur Einträge zurückgegeben, die den gewünschten Zustand zu berücksichtigen. Der Filter stellt einen Wert, der von Membern oder bitweisen Kombinationen von Elementen der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealthStatesFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedApplicationHealthStatesFilter.ToString " />
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
            Gibt eine Zeichenfolgendarstellung des Filters zurück.
            </summary>
        <returns>Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Health.DeployedApplicationHealthStatesFilter" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>