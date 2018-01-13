<Type Name="IWithPerSiteScaling" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithPerSiteScaling">
  <TypeSignature Language="C#" Value="public interface IWithPerSiteScaling" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPerSiteScaling" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithPerSiteScaling" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPerSiteScaling" />
  <TypeSignature Language="F#" Value="type IWithPerSiteScaling = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Ein app Service-plan Definition ermöglicht pro Website, die Skalierung der Konfiguration festgelegt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPerSiteScaling">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithCreate WithPerSiteScaling (bool perSiteScaling);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithCreate WithPerSiteScaling(bool perSiteScaling) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithPerSiteScaling.WithPerSiteScaling(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPerSiteScaling (perSiteScaling As Boolean) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithPerSiteScaling : bool -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithCreate" Usage="iWithPerSiteScaling.WithPerSiteScaling perSiteScaling" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="perSiteScaling" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="perSiteScaling">Wenn Sie jeden Standort einzeln skaliert werden kann.</param>
        <summary>
            Gibt an, ob Skalierung pro Website aktiviert.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>