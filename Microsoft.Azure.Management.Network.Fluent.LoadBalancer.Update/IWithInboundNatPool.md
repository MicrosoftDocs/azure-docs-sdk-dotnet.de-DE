<Type Name="IWithInboundNatPool" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatPool">
  <TypeSignature Language="C#" Value="public interface IWithInboundNatPool" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithInboundNatPool" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithInboundNatPool" />
  <TypeSignature Language="F#" Value="type IWithInboundNatPool = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Legen Sie die Phase eines Laden des Lastenausgleichsmoduls Updates zulassen, um einen neuen eingehenden NAT-Pool für eine VM-Skalierungsgruppe zu erstellen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineInboundNatPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineInboundNatPool (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineInboundNatPool(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatPool.DefineInboundNatPool(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineInboundNatPool (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineInboundNatPool : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;" Usage="iWithInboundNatPool.DefineInboundNatPool name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der eingehenden NAT-Pool.</param>
        <summary>
            Beginn der Definition einer neuen, eingehenden NAT-Pool an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der neue eingehende NAT-Pool-Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateInboundNatPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Update.IUpdate UpdateInboundNatPool (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Update.IUpdate UpdateInboundNatPool(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatPool.UpdateInboundNatPool(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateInboundNatPool (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateInboundNatPool : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Update.IUpdate" Usage="iWithInboundNatPool.UpdateInboundNatPool name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der eingehenden NAT-Pool zu aktualisieren.</param>
        <summary>
            Startet die Beschreibung eines Updates zu einem vorhandenen eingehenden NAT-Pool an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase des eingehenden NAT-Pool Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutInboundNatPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutInboundNatPool (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutInboundNatPool(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatPool.WithoutInboundNatPool(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutInboundNatPool (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutInboundNatPool : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate" Usage="iWithInboundNatPool.WithoutInboundNatPool name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des vorhandenen Pool für eingehende NAT auf dieses Lastenausgleichsmodul.</param>
        <summary>
            Entfernt den angegebenen eingehenden NAT-Pool aus dem Lastenausgleich.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>