<Type Name="IWithInboundNatRule" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatRule">
  <TypeSignature Language="C#" Value="public interface IWithInboundNatRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithInboundNatRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithInboundNatRule" />
  <TypeSignature Language="F#" Value="type IWithInboundNatRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase eines Lastenausgleichs aktualisieren definieren, entfernen oder bearbeiten die NAT-Eingangsregeln ermöglicht.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineInboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineInboundNatRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineInboundNatRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatRule.DefineInboundNatRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineInboundNatRule (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineInboundNatRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;" Usage="iWithInboundNatRule.DefineInboundNatRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name für die eingehende NAT-Regel.</param>
        <summary>
            Beginn der Definition einer neuen NAT-Eingangsregel.
            Die Definition muss mit einem Aufruf von LoadBalancerInboundNatRule.UpdateDefinitionStages.WithAttach.attach() abgeschlossen werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase des der neuen Regel für eingehende NAT Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateInboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Update.IUpdate UpdateInboundNatRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Update.IUpdate UpdateInboundNatRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatRule.UpdateInboundNatRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateInboundNatRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateInboundNatRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Update.IUpdate" Usage="iWithInboundNatRule.UpdateInboundNatRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der eingehenden NAT-Regel aktualisiert.</param>
        <summary>
            Startet die Beschreibung der Aktualisierung einer vorhandenen eingehenden NAT-Regel an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase des eingehenden NAT-Regel-Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutInboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutInboundNatRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutInboundNatRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatRule.WithoutInboundNatRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutInboundNatRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutInboundNatRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate" Usage="iWithInboundNatRule.WithoutInboundNatRule name" />
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
        <param name="name">Der Name einer vorhandenen eingehenden NAT-Regel für dieses Lastenausgleichsmodul.</param>
        <summary>
            Entfernt die angegebene NAT-Eingangsregel aus dem Lastenausgleich.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>