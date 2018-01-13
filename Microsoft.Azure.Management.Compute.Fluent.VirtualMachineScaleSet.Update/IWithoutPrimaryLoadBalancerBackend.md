<Type Name="IWithoutPrimaryLoadBalancerBackend" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerBackend">
  <TypeSignature Language="C#" Value="public interface IWithoutPrimaryLoadBalancerBackend" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithoutPrimaryLoadBalancerBackend" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerBackend" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithoutPrimaryLoadBalancerBackend" />
  <TypeSignature Language="F#" Value="type IWithoutPrimaryLoadBalancerBackend = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der VM-Skalierungsgruppe festgelegt Update ermöglicht die Zuordnung zwischen der primären Netzwerkschnittstellenkonfiguration und eine Back-End-eines Lastenausgleichs entfernen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutPrimaryInternalLoadBalancerBackends">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternalLoadBalancerBackends (params string[] backendNames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternalLoadBalancerBackends(string[] backendNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerBackend.WithoutPrimaryInternalLoadBalancerBackends(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrimaryInternalLoadBalancerBackends (ParamArray backendNames As String()) As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrimaryInternalLoadBalancerBackends : string[] -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithoutPrimaryLoadBalancerBackend.WithoutPrimaryInternalLoadBalancerBackends backendNames" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backendNames" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="backendNames">Vorhandene Back-End-Namen.</param>
        <summary>
            Entfernt die Zuordnungen zwischen der primären Schnittstelle Netzwerkkonfiguration und die angegebene Back-Ends des internen Lastenausgleichs an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPrimaryInternetFacingLoadBalancerBackends">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternetFacingLoadBalancerBackends (params string[] backendNames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternetFacingLoadBalancerBackends(string[] backendNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerBackend.WithoutPrimaryInternetFacingLoadBalancerBackends(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrimaryInternetFacingLoadBalancerBackends (ParamArray backendNames As String()) As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrimaryInternetFacingLoadBalancerBackends : string[] -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithoutPrimaryLoadBalancerBackend.WithoutPrimaryInternetFacingLoadBalancerBackends backendNames" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backendNames" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="backendNames">Vorhandene Back-End-Namen.</param>
        <summary>
            Entfernt die Zuordnungen zwischen der primären Netzwerkschnittstellenkonfiguration und das angegebene Back-Ends des Lastenausgleichs Internetzugriff an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>