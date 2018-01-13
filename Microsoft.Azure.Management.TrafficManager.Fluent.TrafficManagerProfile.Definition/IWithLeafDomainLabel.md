<Type Name="IWithLeafDomainLabel" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithLeafDomainLabel">
  <TypeSignature Language="C#" Value="public interface IWithLeafDomainLabel" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLeafDomainLabel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithLeafDomainLabel" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLeafDomainLabel" />
  <TypeSignature Language="F#" Value="type IWithLeafDomainLabel = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Traffic Manager Profildefinition ermöglicht den relativen DNS-Namen angeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithLeafDomainLabel">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod WithLeafDomainLabel (string dnsLabel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod WithLeafDomainLabel(string dnsLabel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithLeafDomainLabel.WithLeafDomainLabel(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLeafDomainLabel (dnsLabel As String) As IWithTrafficRoutingMethod" />
      <MemberSignature Language="F#" Value="abstract member WithLeafDomainLabel : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod" Usage="iWithLeafDomainLabel.WithLeafDomainLabel dnsLabel" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dnsLabel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="dnsLabel">Der relative DNS-Name des Profils.</param>
        <summary>
            Geben Sie den relativen DNS-Namen des Profils.
            Der vollqualifizierte Domänenname (FQDN) wird automatisch erstellt werden, durch den Rest der Domäne auf diese Bezeichnung anhängen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>