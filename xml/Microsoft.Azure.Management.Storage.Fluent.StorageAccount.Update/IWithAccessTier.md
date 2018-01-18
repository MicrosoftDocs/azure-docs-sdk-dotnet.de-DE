<Type Name="IWithAccessTier" FullName="Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IWithAccessTier">
  <TypeSignature Language="C#" Value="public interface IWithAccessTier" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAccessTier" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IWithAccessTier" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAccessTier" />
  <TypeSignature Language="F#" Value="type IWithAccessTier = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f84e2-101">Eine BLOB-Speicher-Konto Update Stufe ermöglicht zugriffstarifs angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="f84e2-101">A blob storage account update stage allowing access tier to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAccessTier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate WithAccessTier (Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier accessTier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate WithAccessTier(valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier accessTier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IWithAccessTier.WithAccessTier(Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier)" />
      <MemberSignature Language="F#" Value="abstract member WithAccessTier : Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier -&gt; Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate" Usage="iWithAccessTier.WithAccessTier accessTier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessTier" Type="Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier" />
      </Parameters>
      <Docs>
        <param name="accessTier"><span data-ttu-id="f84e2-102">Der Wert für den Access-Ebene.</span><span class="sxs-lookup"><span data-stu-id="f84e2-102">The access tier value.</span></span></param>
        <summary>
            <span data-ttu-id="f84e2-103">Gibt die Access-Ebene für die Abrechnung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f84e2-103">Specifies the access tier used for billing.</span></span>
            <span data-ttu-id="f84e2-104">Zugriffstarifs kann mehr als einmal alle 7 Tage (168 Stunden) geändert werden.</span><span class="sxs-lookup"><span data-stu-id="f84e2-104">Access tier cannot be changed more than once every 7 days (168 hours).</span></span>
            <span data-ttu-id="f84e2-105">Zugriffstarifs kann nicht für StandardLRS, StandardGRS, StandardRAGRS oder PremiumLRS Kontotypen festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="f84e2-105">Access tier cannot be set for StandardLRS, StandardGRS, StandardRAGRS, or PremiumLRS account types.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f84e2-106">Die nächste Phase der Aktualisierung des Speicher-Dienstkontos.</span><span class="sxs-lookup"><span data-stu-id="f84e2-106">The next stage of storage account update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>