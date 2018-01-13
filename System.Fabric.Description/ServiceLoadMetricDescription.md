<Type Name="ServiceLoadMetricDescription" FullName="System.Fabric.Description.ServiceLoadMetricDescription">
  <TypeSignature Language="C#" Value="public class ServiceLoadMetricDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceLoadMetricDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceLoadMetricDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceLoadMetricDescription" />
  <TypeSignature Language="F#" Value="type ServiceLoadMetricDescription = class" />
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
      <para>Gibt einer Metrik für den Lastenausgleich einen Dienst während der Laufzeit.</para>
    </summary>
    <remarks>
      <para>Beachten Sie, um zu gewährleisten, dass die Metriken für optional ist, da Service Fabric Standard Metriken verwendet. Geben Sie Metriken aus, nur dann, wenn der Dienst erweiterte Funktionen erfordert wie Lastenausgleich, die für den Lastenausgleich auf bestimmten Knoten Merkmale und Ressourcen basiert.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceLoadMetricDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceLoadMetricDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ServiceLoadMetricDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceLoadMetricDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="System.Fabric.Description.ServiceLoadMetricDescription.Name" />
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
          <para>Ruft ab oder legt den Namen der Metrik. </para>
        </summary>
        <value>
          <para>Der Name der Metrik.</para>
        </value>
        <remarks>
          <para>Wenn der Dienst auswählt <see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" /> während der Laufzeit, der Name, über die <see cref="T:System.Fabric.LoadMetric" /> an, die Zeit sollte mit dem Namen übereinstimmen, die im angegebenen <see cref="P:System.Fabric.Description.ServiceLoadMetricDescription.Name" /> genau.</para>
          <para>Beachten Sie, dass metriknamen Groß-/Kleinschreibung unterschieden werden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryDefaultLoad">
      <MemberSignature Language="C#" Value="public int PrimaryDefaultLoad { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrimaryDefaultLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceLoadMetricDescription.PrimaryDefaultLoad" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryDefaultLoad As Integer" />
      <MemberSignature Language="F#" Value="member this.PrimaryDefaultLoad : int with get, set" Usage="System.Fabric.Description.ServiceLoadMetricDescription.PrimaryDefaultLoad" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("PrimaryDefaultLoad in ServiceLoadMetricDescription is deprecated, please use StatefulServiceLoadMetricDescription instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Sie finden Sie in der abgeleiteten Klasse <see cref="T:System.Fabric.Description.StatefulServiceLoadMetricDescription" /> oder <see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" /> für die Verwendung.</para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>Diese Eigenschaft ist veraltet, verwenden Sie die entsprechende Eigenschaft in der abgeleiteten Klasse.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryDefaultLoad">
      <MemberSignature Language="C#" Value="public int SecondaryDefaultLoad { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SecondaryDefaultLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceLoadMetricDescription.SecondaryDefaultLoad" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryDefaultLoad As Integer" />
      <MemberSignature Language="F#" Value="member this.SecondaryDefaultLoad : int with get, set" Usage="System.Fabric.Description.ServiceLoadMetricDescription.SecondaryDefaultLoad" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("SecondaryDefaultLoad in ServiceLoadMetricDescription is deprecated, please use StatefulServiceLoadMetricDescription instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Sie finden Sie in der abgeleiteten Klasse <see cref="T:System.Fabric.Description.StatefulServiceLoadMetricDescription" /> oder <see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" /> für die Verwendung.</para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>Diese Eigenschaft ist veraltet, verwenden Sie die entsprechende Eigenschaft in der abgeleiteten Klasse.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public string ToString (bool isStateful);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string ToString(bool isStateful) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceLoadMetricDescription.ToString(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToString (isStateful As Boolean) As String" />
      <MemberSignature Language="F#" Value="override this.ToString : bool -&gt; string" Usage="serviceLoadMetricDescription.ToString isStateful" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="isStateful" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="isStateful">To be added.</param>
        <summary>
            Details der Schöndruck <see cref="T:System.Fabric.Description.StatefulServiceLoadMetricDescription" /> oder <see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" />.
            </summary>
        <returns>Eine Zeichenfolgendarstellung <see cref="T:System.Fabric.Description.StatefulServiceLoadMetricDescription" /> oder <see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Weight">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServiceLoadMetricWeight Weight { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ServiceLoadMetricWeight Weight" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceLoadMetricDescription.Weight" />
      <MemberSignature Language="VB.NET" Value="Public Property Weight As ServiceLoadMetricWeight" />
      <MemberSignature Language="F#" Value="member this.Weight : System.Fabric.Description.ServiceLoadMetricWeight with get, set" Usage="System.Fabric.Description.ServiceLoadMetricDescription.Weight" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceLoadMetricWeight</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Bestimmt die metrische Gewichtung relativ zu die sonstigen Metriken, die für diesen Dienst konfiguriert sind. Wenn zwei Metriken in Konflikt, annehmen bevorzugt der Clusterressourcen-Manager während der Laufzeit die Metrik mit der höheren Gewichtung.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.Description.ServiceLoadMetricWeight" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>