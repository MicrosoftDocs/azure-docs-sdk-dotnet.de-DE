<Type Name="ServiceHealthStatesFilter" FullName="System.Fabric.Health.ServiceHealthStatesFilter">
  <TypeSignature Language="C#" Value="public sealed class ServiceHealthStatesFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceHealthStatesFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceHealthStatesFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceHealthStatesFilter" />
  <TypeSignature Language="F#" Value="type ServiceHealthStatesFilter = class" />
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
      <para>Stellt filter für <see cref="T:System.Fabric.Health.ServiceHealthState" /> Objekte.</para>
    </summary>
    <remarks>Der Filter kann verwendet werden, <see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" /> angeben, welche untergeordneten Dienst als Teil des zurückgegeben werden sollen <see cref="T:System.Fabric.Health.ApplicationHealth" />.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceHealthStatesFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStatesFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.ServiceHealthStatesFilter" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public long HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStatesFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As Long" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : int64 with get, set" Usage="System.Fabric.Health.ServiceHealthStatesFilter.HealthStateFilter" />
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
          <para>ALS VERALTET MARKIERT. Ruft ab oder legt ihn fest des Filters für den aggregierten Zustand der <see cref="T:System.Fabric.Health.ServiceHealthState" /> Einträge in der Auflistung. </para>
        </summary>
        <value>
          <para>Der Wert des Filters. Der Wert stammt von Membern oder bitweisen Kombination von Membern der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</para>
        </value>
        <remarks>Diese Eigenschaft ist veraltet. Verwenden Sie stattdessen <see cref="P:System.Fabric.Health.ApplicationHealthStatesFilter.HealthStateFilterValue" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilterValue">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilterValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilterValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStatesFilter.HealthStateFilterValue" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilterValue As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilterValue : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.ServiceHealthStatesFilter.HealthStateFilterValue" />
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
            Ruft ab oder legt ihn fest des Filters für den aggregierten Zustand der <see cref="T:System.Fabric.Health.ServiceHealthState" /> Einträge in der Auflistung. 
            </summary>
        <value>Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.ServiceHealthState" /> Einträge.</value>
        <remarks>Die Eingabesammlung wird gefiltert, dass nur Einträge zurückgegeben, die den gewünschten Zustand zu berücksichtigen. Der Filter stellt einen Wert, der von Membern oder bitweisen Kombinationen von Elementen der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStatesFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceHealthStatesFilter.ToString " />
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
        <returns>Eine Zeichenfolgendarstellung des Filters.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>