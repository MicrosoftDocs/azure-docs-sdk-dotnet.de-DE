<Type Name="IWithProfileStatus" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithProfileStatus">
  <TypeSignature Language="C#" Value="public interface IWithProfileStatus" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithProfileStatus" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithProfileStatus" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithProfileStatus" />
  <TypeSignature Language="F#" Value="type IWithProfileStatus = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a9aae-101">Die Phase der Traffic Manager-Profil aktualisieren zulassen, deaktivieren oder aktivieren das Profil.</span><span class="sxs-lookup"><span data-stu-id="a9aae-101">The stage of the traffic manager profile update allowing to disable or enable the profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithProfileStatusDisabled">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithProfileStatusDisabled ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithProfileStatusDisabled() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithProfileStatus.WithProfileStatusDisabled" />
      <MemberSignature Language="VB.NET" Value="Public Function WithProfileStatusDisabled () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithProfileStatusDisabled : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate" Usage="iWithProfileStatus.WithProfileStatusDisabled " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a9aae-102">Geben Sie an, dass das Profil deaktiviert werden muss.</span><span class="sxs-lookup"><span data-stu-id="a9aae-102">Specify that the profile needs to be disabled.</span></span>
            <span data-ttu-id="a9aae-103">Deaktivieren das Profil deaktiviert Datenverkehr an alle Endpunkte im Profil.</span><span class="sxs-lookup"><span data-stu-id="a9aae-103">Disabling the profile will disables traffic to all endpoints in the profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a9aae-104">Die nächste Phase des Traffic Manager-Profil Updates.</span><span class="sxs-lookup"><span data-stu-id="a9aae-104">The next stage of the traffic manager profile update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithProfileStatusEnabled">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithProfileStatusEnabled ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithProfileStatusEnabled() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithProfileStatus.WithProfileStatusEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Function WithProfileStatusEnabled () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithProfileStatusEnabled : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate" Usage="iWithProfileStatus.WithProfileStatusEnabled " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a9aae-105">Geben Sie an, dass das Profil muss aktiviert sein.</span><span class="sxs-lookup"><span data-stu-id="a9aae-105">Specify that the profile needs to be enabled.</span></span>
            <span data-ttu-id="a9aae-106">Aktivieren das Profil können Datenverkehr an alle Endpunkte im Profil.</span><span class="sxs-lookup"><span data-stu-id="a9aae-106">Enabling the profile will enables traffic to all endpoints in the profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a9aae-107">Die nächste Phase des Traffic Manager-Profil Updates.</span><span class="sxs-lookup"><span data-stu-id="a9aae-107">The next stage of the traffic manager profile update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>