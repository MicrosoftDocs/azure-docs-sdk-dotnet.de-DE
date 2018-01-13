<Type Name="PoolUsageMetrics" FullName="Microsoft.Azure.Batch.PoolUsageMetrics">
  <TypeSignature Language="C#" Value="public class PoolUsageMetrics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolUsageMetrics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.PoolUsageMetrics" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolUsageMetrics" />
  <TypeSignature Language="F#" Value="type PoolUsageMetrics = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die nutzungsmetrik für eine einzelnes Pool in einem bestimmten Zeitraum.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DataEgressGiB">
      <MemberSignature Language="C#" Value="public double DataEgressGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DataEgressGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.DataEgressGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataEgressGiB As Double" />
      <MemberSignature Language="F#" Value="member this.DataEgressGiB : double" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.DataEgressGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Cross Datenausgang Center Netzwerk aus dem Pool während dieses Intervalls schlägt in Gibibytes ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataIngressGiB">
      <MemberSignature Language="C#" Value="public double DataIngressGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DataIngressGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.DataIngressGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataIngressGiB As Double" />
      <MemberSignature Language="F#" Value="member this.DataIngressGiB : double" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.DataIngressGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Cross Data Center Netzwerk eingehend an den Pool während dieses Intervalls schlägt in Gibibytes ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public DateTime EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.EndTime : DateTime" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Endzeit des aggregationsintervalls für diesen Eintrag ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolId">
      <MemberSignature Language="C#" Value="public string PoolId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PoolId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.PoolId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PoolId As String" />
      <MemberSignature Language="F#" Value="member this.PoolId : string" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.PoolId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Id des Pools, dessen Metriken in diesem Eintrag aggregiert werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Startzeit des aggregationsintervalls behandelt, die durch diesen Eintrag ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCoreHours">
      <MemberSignature Language="C#" Value="public double TotalCoreHours { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 TotalCoreHours" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.TotalCoreHours" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCoreHours As Double" />
      <MemberSignature Language="F#" Value="member this.TotalCoreHours : double" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.TotalCoreHours" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die gesamte kernstunden im Pool verwendet wird, während dieses aggregationsintervalls ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineSize">
      <MemberSignature Language="C#" Value="public string VirtualMachineSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.VirtualMachineSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineSize As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineSize : string" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.VirtualMachineSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Größe der virtuellen Computer im Pool.  Alle virtuellen Computer in einem Pool haben die gleiche Größe.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Informationen zu den verfügbaren Größen von virtuellen Maschinen für Cloud-Dienste-Pools (Pools mit erstellt eine <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />), finden Sie unter https://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/. Batch unterstützt alle Cloud-Dienste VM-Größen sind ExtraSmall mit Ausnahme von.</para>
          <para>Informationen zu den verfügbaren VM-Größen für Anwendungspools, die mithilfe von Images von virtuellen Maschinen Marketplace (mit erstellten Ressourcenpools einer <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />) finden Sie unter https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/ oder https:// Azure.Microsoft.com/Documentation/articles/Virtual-Machines-Windows-sizes/. Batch unterstützt alle Azure-VM-Größen außer STANDARD_A0 und die mit Premium-Speicher (z. B. STANDARD_GS STANDARD_DS und STANDARD_DSV2-Serie).</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>