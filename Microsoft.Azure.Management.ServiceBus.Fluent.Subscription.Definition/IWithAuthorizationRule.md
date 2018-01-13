<Type Name="IWithAuthorizationRule" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithAuthorizationRule">
  <TypeSignature Language="C#" Value="public interface IWithAuthorizationRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAuthorizationRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithAuthorizationRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAuthorizationRule" />
  <TypeSignature Language="F#" Value="type IWithAuthorizationRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f9df1-101">Die Stufe der die Warteschlangendefinition, sodass Sie eine Autorisierungsregel für den Zugriff auf das Abonnement hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="f9df1-101">The stage of the queue definition allowing to add an authorization rule for accessing the subscription.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewAuthorizationRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate WithNewAuthorizationRule (string name, params Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights[] rights);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate WithNewAuthorizationRule(string name, valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights[] rights) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithAuthorizationRule.WithNewAuthorizationRule(System.String,Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewAuthorizationRule (name As String, ParamArray rights As AccessRights()) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewAuthorizationRule : string * Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights[] -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate" Usage="iWithAuthorizationRule.WithNewAuthorizationRule (name, rights)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="rights" Type="Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="f9df1-102">Name der Regel.</span><span class="sxs-lookup"><span data-stu-id="f9df1-102">Rule name.</span></span></param>
        <param name="rights"><span data-ttu-id="f9df1-103">Regel-Rechte.</span><span class="sxs-lookup"><span data-stu-id="f9df1-103">Rule rights.</span></span></param>
        <summary>
            <span data-ttu-id="f9df1-104">Erstellt eine Autorisierungsregel für das Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="f9df1-104">Creates an authorization rule for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f9df1-105">Nächste Stufe der Abonnementdefinition.</span><span class="sxs-lookup"><span data-stu-id="f9df1-105">Next stage of the subscription definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>